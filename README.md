# Check if two words are anagrams
# Example:
# find_anagrams("hello", "check") --> False
# find_anagrams("below", "elbow") --> True

# [assignment] Add your code here

def find_anagram(str1, str2):

    # check the sorted strings

    if (sorted(str1) == sorted(str2)):

        return True

    else:

        return False


str1 = "secure"
str2 = "rescue"

print(find_anagram(str1, str2))
