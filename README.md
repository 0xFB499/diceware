# Diceware Passphrase Generator
Pretty self-explainatory, this script just translate numbers to words from a words list file.

This script **can** generate random numbers. But you should do it yourself with some dice :)

More on [diceware](https://en.wikipedia.org/wiki/Diceware)

--------
## Usage
```
python main.py <path/to/wordlist-file> (-f <path/to/numbers-file> | -g <n. words to generate> | -i)
```
where:

- a _wordlist_ is a file that contains some lines in the format ```<digits> <word>``` (every other text is ignore)
- a _numberlist_ is a file that contains a number for every line
- ```-i``` make input interactive: give any number and print the associated word
- ```-g``` request _n_ (preferably > 7) numbers from [random.org](https://www.random.org) and translate into words
- ```-f``` read numbers from file
