# Finnish Vowel Harmony

Scary for many is the Finnish language, but fear not; there is some logic to it. One of the most logical parts of Finnish language is it's vowel harmony.

What is vowel harmony?
It is situation where a suffix is added to a word and the vowel of the suffix changes based on the word itself.

For example with -ssA case:
- Talo(ssa) (in house)
- Metsä(ssä) (in forest)

Rules of Finnish vowel harmony:
Vowels are separeted into 3 categories:
- Back vowels: a, o, u
- Front vowels: ä, ö, y
- Neutral vowels: e, i
Usage of these vowels is shown with a capital letter. suffix -llA, has capital A. That means that 'A' will be replaced either with a or ä. Same goes with O -> o or ö and U -> u or y.

Which harmony does the word use?
The harmony is determined by looking at last vowel of the word.
If the vowel is neutral, then we look at one before that. If all the vowels are neutral, then we use front harmony.
If the vowel isn't a neutral one, then the harmony is the one where the vowel belongs.

Additionally, if the word is a combineword then we only look at the last word of the combineword.
Example:
takapenkki -> taka + penkki, only looking for harmony from penkki.

Obviously determening where words change is way too challenging, so it is enough that if word has a line connecting two words, then we use the last word.
Examples:
uima-allas -> back harmony.
koriste-esine -> front harmony.

Write a function that returns 0 if the word has back harmony and 1 if it has front harmony.