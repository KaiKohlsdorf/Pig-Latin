Describe: vowelCounter():

Test: "It will recognize a single vowel."
Code: vowelCounter("a")
Expected Output: "a"

Test: "It will recognize a single consonant."
Code: consonantCounter("b")
Expected Output: "b"

Test: "It will add 'way' to the end of words that begin with a vowel."
Code: pigLatin("a");
Expected Output: "away"

Test: "It will move move the first consecutive consenants to the end and add 'ay'."
Code: pigLatin("code");
Expected Output: "odecay"

Test: "If the consonant equals q, it will move the second letter to the end with it and add 'ay'."
Code: pigLatin("quick");
Expected Output: "ickquay"