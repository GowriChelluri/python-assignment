A string is said to be a palindrome if the reverse of the string is the same as the string. For example, “radar” is a palindrome, but “radix” is not a palindrome.

    Remove non-alphanumeric characters: spaces, punctuation, and capitalization don't matter in palindrome checks, so you might want to remove them from the string before proceeding.
    Compare characters: Start by comparing the characters at the beginning and end of the string. If they're the same, move inward and continue the comparison. If they're different at any point during this process, the string is not a palindrome.
