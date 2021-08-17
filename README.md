The aim of this project is to provide solutions to English text encoded monoalphabetically.

I'll use the [frequencies discovered by Beker and Piper](https://www.nku.edu/~christensen/092mat483%20Friedman%20test%20summary.pdf).

> Consideration: these are from the 20th century and I wonder if the frequencies have evolved since then. I also don't know how large or well-selected the sample text was.

I'm setting the problem of polyalphabetic substitution aside in favor of solving the simpler monoalphabetic substitution cipher first.

I will:

1. Learn how frequency counter solutions are implemented in golang, and identify what aspects I'll need to change for my problem.
2. Choose how to introduce the Beker/Piper frequencies to my problem. How to store them so I can compare them against the results of my frequency counter?
3. Manage edge cases. An easy but maybe not as powerful way would be to manage against length of text.
