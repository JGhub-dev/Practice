#include <stdio.h>
#include <string.h>
#include <stdlib.h>

char *strrev(char *str) {
    int len = strlen(str);
  
  	// Temporary char array to store the
    // reversed string
    char *rev = (char *)malloc
      (sizeof(char) * (len + 1));
  
    // Reversing the string
    for (int i = 0; i < len; i++) {
        rev[i] = str[len - i - 1];
    }
    rev[len] = '\0';
    return rev;
}

void isPalindrome(char *str) {

    // Reversing the string
    char *rev = strrev(str);

    // Check if the original and reversed
  	// strings are equal
    if (strcmp(str, rev) == 0)
        printf("\"%s\" is palindrome.\n",
               str);
    else
        printf("\"%s\" is not palindrome.\n",
               str);
}

int main() {
    
  	// Cheking for palindrome strings
	isPalindrome("madam");
  	isPalindrome("hello");

    return 0;
}
