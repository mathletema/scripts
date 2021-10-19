#!/usr/bin/env python3

import sys
import random

VOWELS = "aeiouy"
CONSONANTS = "bcdfghjklmnpqrstvwxz"
ALPHABET = "abcdefghijklmnopqrstuvwxyz"

word = ""

type = sys.argv[1]

for c in type:
    if (c == "0"):
        word += random.choice(VOWELS)
    elif (c == "1"):
        word += random.choice(CONSONANTS)
    elif (c == "*"):
        word += random.choice(ALPHABET)
    else:
        word += c;
print(word)