# Xeno Website

Веб-сайт для Xeno - The Best Key-Less Executor

## Размещение на GitHub Pages

### Шаг 1: Создайте репозиторий на GitHub

1. Перейдите на [GitHub.com](https://github.com) и войдите в свой аккаунт
2. Нажмите кнопку "+" в правом верхнем углу и выберите "New repository"
3. Назовите репозиторий (например, `xeno-website` или `my-site`)
4. Выберите "Public" (GitHub Pages работает с публичными репозиториями на бесплатном плане)
5. **НЕ** ставьте галочки на "Initialize this repository with a README"
6. Нажмите "Create repository"

### Шаг 2: Загрузите файлы в репозиторий

#### Вариант A: Через веб-интерфейс GitHub

1. На странице созданного репозитория нажмите "uploading an existing file"
2. Перетащите файлы `index.html` и `styles.css` в окно браузера
3. Нажмите "Commit changes"

#### Вариант B: Через Git (командная строка)

```bash
# Инициализируйте Git репозиторий
git init

# Добавьте файлы
git add index.html styles.css README.md

# Сделайте первый коммит
git commit -m "Initial commit: Xeno website"

# Добавьте удаленный репозиторий (замените YOUR_USERNAME и YOUR_REPO на свои значения)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git

# Загрузите файлы на GitHub
git branch -M main
git push -u origin main
```

### Шаг 3: Включите GitHub Pages

1. В вашем репозитории на GitHub перейдите в **Settings** (Настройки)
2. В левом меню найдите раздел **Pages**
3. В разделе "Source" выберите:
   - **Branch**: `main` (или `master`, если используете старую ветку)
   - **Folder**: `/ (root)`
4. Нажмите **Save**

### Шаг 4: Дождитесь публикации

GitHub обработает ваш сайт в течение 1-2 минут. После этого ваш сайт будет доступен по адресу:

```
https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/
```

Например: `https://username.github.io/xeno-website/`

### Проверка сайта

После публикации вы можете:
- Открыть сайт по ссылке выше
- В настройках Pages увидеть зеленую галочку и ссылку на ваш сайт

## Локальный просмотр

Чтобы просмотреть сайт локально, просто откройте файл `index.html` в браузере.

## Структура проекта

```
Site/
├── index.html      # Главная страница
├── styles.css      # Стили сайта
└── README.md       # Этот файл
```

## Дополнительная информация

- [Документация GitHub Pages](https://docs.github.com/en/pages)
- [Создание сайта на GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

