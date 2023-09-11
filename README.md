# Інструкція до виконання

Всі лабораторні роботи по Вашій темі будуть виконуватися в межах одного проєкту. Зокрема цей репозиторій і буде відображати Ваш прогрес над виконанням робіт.

## 1. Структура репозиторію (робочої директорії)
Ваша директорія повинна містити наступні елементи:
- ./architecture/ (Тут будуть всі Ваші діаграми)
- ./reports/      (Тут будуть всі Ваші звіти)
- ./src/          (Тут буде код проєкту)
- README.md       (див. п.1)
Ось приклад:
<img width="457" alt="image" src="https://github.com/mrkolesnik/sdt-template/assets/116352252/6987c10f-69eb-42f7-ad8f-a46d42613bc1">

<br/>

## 2. Звіт про виконану роботу
- Звіт повинен мати назву у форматі `[Група] [Прізвище 1] LAB[номер роботи].pdf` англійською мовою, наприклад
```
IA-29 Stallone LAB4.pdf
```
- Оформлення документу здійснювати згідно [витягу](https://docs.google.com/document/d/1UmpdH9SZw1DKkKhtlfwXfm3f5M9gAqwD/edit?usp=sharing&ouid=101517430584893715343&rtpof=true&sd=true) або [стандарту кафедри](https://drive.google.com/file/d/18c0hqjAK6vYigSnc5CFiCfKoN0j5Fryt/view?usp=sharing)

<br/>

## 3. README 
Файл README.md - це фактично кумулятивний звіт Вашої роботи за семестр. Тобто після виконання кожної роботи його потрібно буде оновлювати.
Цей файл обов'язково потрібно змінити при виконанні 2 ЛР таким чином, щоб у ньому була присутня наступна інформація: Група Прізвище Ім'я і Номер роботи. 
Для цього потрібно видалити весь вміст файлу і можна використати наступний шаблон (ось [приклад](README-EXAMPLE.md)):

```markdown
# [Група] [Прізвище] [Ім'я]
## Тема: [Ваша тема]

...Content...
```

Якщо хочете залишити дані інструкції десь поруч, просто переназвіть цей файл на `INSTRUCTIONS.md` наприклад і створіть новий `README.md`.

Після виконання лабораторної роботи в зону `...Content...` потрібно додавати новий розділ у вигляді:

```markdown
---
### ЛР [Номер роботи]
[Звіт](тут має бути посилання на звіт з папки reports) наприклад [Звіт](./reports/IA-01 Winchester LAB2.pdf)

...Тут можна додати діаграми...

Висновки:
> Висновки зі звіту
> Якщо текст багаторядковий, тоді використовувати символ `>` на кожному рядку спочатку
---

```
<br/>

## 4. Подача роботи на перевірку і підготовка до захисту
Основний час Ви працюєте в гілці `main`. В цій гілці Ваш проєкт буде розвиватися щотижня. Щойно Ви завершили виконання роботи, тобто виконали наступні кроки:
1. Додали звіт до директорії `reports`
2. Додали діаграми в директорії `architecture`
3. Написали певну реалізацію в диеркторії `src`
4. Оновили `README.md`

Вам потрібно свою роботу зафіксувати. Для цього потрібно створити `tag` у Вашому репозиторії, на github він існує разом із релізом роботи. Тому кожна Ваша лабораторна робота - це реліз.
На github Ви можете створити тег наступним чином:
1. Клікнути на вкладку, де пише `tags`
<img width="764" alt="image" src="https://github.com/mrkolesnik/sdt-template/assets/116352252/32d23646-8a80-452b-a6f8-6461e7fd6b24">

2. Далі на кнопку `Create new release`
<img width="853" alt="image" src="https://github.com/mrkolesnik/sdt-template/assets/116352252/5b5fd9b1-30b0-4440-8616-4d0b4f48896f">

3. Choose tag -> даєте назву тегу у форматі `lab-(номер ЛР)` -> **Create new tag:** on publish
4. Змінити заголовок релізу на текст у форматі: ЛР (номер ЛР)
5. В описі достатньо написати текст у форматі як і п.4.
<img width="733" alt="image" src="https://github.com/mrkolesnik/sdt-template/assets/116352252/43debecc-55d1-42cf-b20e-f65f36e64fdc">

Наприклад:

<img width="702" alt="image" src="https://github.com/mrkolesnik/sdt-template/assets/116352252/038e7806-2c35-46a2-b034-8cb7522ce262">

6. Publish release

<img width="723" alt="image" src="https://github.com/mrkolesnik/sdt-template/assets/116352252/27cc378e-8475-4b1e-be29-0f5b6b34562b">




