# Чтение файла с текстом Библии
def read_bible(file_path):
    with open(file_path, 'r', encoding='utf-8') as file:
        verses = file.readlines()
    return verses

# Функция для поиска стихов по ключевым словам
def find_verses(verses, keyword):
    return [verse for verse in verses if keyword.lower() in verse.lower()]

# Путь к файлу с Библией
bible_file = 'bible.txt'

# Чтение стихов Библии
bible_verses = read_bible(bible_file)

# Поиск стихов по ключевому слову
keyword = "любовь"  # пример ключевого слова
matched_verses = find_verses(bible_verses, keyword)

# Вывод найденных стихов
for verse in matched_verses:
    print(verse)
ибо так возлюбил Бог мир что отдал Сына Своего Единородногочто бы каждый верующий в Него не погиб но имел жизнь вечную 👋 Hi, I’m @Oleg85gg-art
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Oleg85gg-art/Oleg85gg-art is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
