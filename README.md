Describe: vowelRecognizer():

Test: "It will recognize a single vowel."
Code: vowelRecognizer("a")
Expected Output: "a"

Test: "It will recognize a single consonant."
Code: consonantRecognizer("b")
Expected Output: "b"

Test: "It will add 'way' to the end of words that begin with a vowel."
Code: pigLatin("a");
Expected Output: "away"

Test: "It will move move the first consecutive consenants to the end and add 'ay'."
Code: pigLatin("code");
Expected Output: "odecay"

Test: "If the last consonant to be taken from the front of the word equals q, it will move the following letter to the end with it and add 'ay'."
Code: pigLatin("quick");
Expected Output: "ickquay"