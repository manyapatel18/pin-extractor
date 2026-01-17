# 🔐 PIN Extractor (Python)

## Description
PIN Extractor is a simple Python program that extracts a secret numeric code from a poem using a positional rule.

Each digit of the PIN is determined by the length of the *n*th word in the *n*th line of the poem.

This project was created as a learning exercise to practice Python fundamentals such as string manipulation, loops, indexing, and functions.

---

## How It Works
1. The poem is split into individual lines  
2. Each line is split into words  
3. For each line, the word at the same index as the line number is selected  
4. The length of that word becomes a digit of the PIN  
5. All digits are concatenated to form the final secret code  

---

## Example

### Input Poem
