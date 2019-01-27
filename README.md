# anagram-validation
This fastest algorithm would be to map each of the 256 ASCII characters to a unique prime number.
Then calculate the product of the string by the fundamental theorem of arithmetic, 2 strings are anagrams if and only if their products are the same.

String listen:

String[0] = "l"
ASCII of "l" = 108 --> primesArray[108] = 223
String[1] = "i"
ASCII of "i" = 105 --> primesArray[105] = 217
String[2] = "s"
ASCII of "s" = 115 --> primesArray[115] = 237
String[3] = "t"
ASCII of "t" = 116 --> primesArray[116] = 239
String[4] = "e"
ASCII of "e" = 101 --> primesArray[101] = 209
String[5] = "n"
ASCII of "n" = 110 --> primesArray[110] = 227

223*217*237*239*209*227 = 130041804466959

For string silent, we will get the same result: 130041804466959.

