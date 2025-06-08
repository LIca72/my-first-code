# my-first-code
Мої навчальні проєкти 


sentence = input("Введіть речення: ")
vowels = "аеєиіїоуюя"
punctuation = ".,!?-–—:;\"'()[]{}"
consonants_only = ""

for letter in sentence.lower():
    if letter not in vowels and letter not in punctuation and letter != " ":
        consonants_only += letter

print("Приголосні літери у реченні:")
for letter in consonants_only:
    print(letter)
