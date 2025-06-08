# my-first-code
Мої навчальні проєкти 


## 🧠 Python code:

```python
sentence = input("Enter a sentence: ")
vowels = "aeiouаеєиіїоуюя"
punctuation = ".,!?—-;:()[]{}\"'"
consonants_only = ""

for letter in sentence.lower():
    if letter not in vowels and letter not in punctuation and letter != " ":
        consonants_only += letter

print("Consonant letters in the sentence:")
for letter in consonants_only:
    print(letter)
