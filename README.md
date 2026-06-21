# Сайт памяти семьи Пешкичевых

Статический сайт для GitHub Pages в память о Ларисе Петровне и Юрии Афанасьевиче Пешкичевых.

## Как опубликовать на GitHub Pages

1. Создайте репозиторий на GitHub, например `family` (под вашим аккаунтом).
2. В этой папке выполните:
   ```bash
   git init
   git add .
   git commit -m "Первая версия сайта памяти"
   git branch -M main
   git remote add origin git@github.com:ВАШ_ЛОГИН/family.git
   git push -u origin main
   ```
3. В настройках репозитория: **Settings → Pages → Source: Deploy from a branch → main / (root)**.
4. Через 1–2 минуты сайт будет доступен по адресу `https://ВАШ_ЛОГИН.github.io/family/`.

## Настроить форму воспоминаний (Formspree)

1. Зарегистрируйтесь на [formspree.io](https://formspree.io/) (бесплатно).
2. Создайте новую форму, привяжите её к `yuriy.pesh@gmail.com`.
3. Скопируйте endpoint вида `https://formspree.io/f/abcd1234`.
4. В [index.html](index.html) замените `REPLACE_WITH_YOUR_FORM_ID` на ваш id.
5. Закоммитьте и запушьте — форма заработает.

## Что добавить позже

- Реальные фотографии в раздел «Фотографии» (положить в `images/` и вставить `<img>`).
- Генеалогическое дерево (можно использовать [familyecho.com](https://www.familyecho.com/) или сгенерировать SVG).
- Тексты в разделы Томск/Рудный/Бердск/Кольцово по мере поступления воспоминаний.
