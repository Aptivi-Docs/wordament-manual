---
description: How do you use it?
---

# 🖥 How to use

Using this library is very simple! Just use the `Wordament` namespace in any piece of code you want to use the library, as in: `using Wordament;`

Just use the `WordManager` class that contains:

* `GetRandomWord()`
* `GetRandomWordConditional(int, string, string)`

These functions call the `InitializeWords()` function to download the list of words and installs the list of words to the words list for the two above functions to use.

If the conditional version is used, you can specify the maximum length of the word, the prefix of the word, the postfix of the word, and the exact word length.
