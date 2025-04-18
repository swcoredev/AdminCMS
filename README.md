# Инструкция для разработчиков AdminCMS

## Подключение к репозиторию GitHub

### 1. Клонировать проект (SSH)
```bash
git clone git@github.com:swcoredev/AdminCMS.git
```

### 2. Перейти в папку проекта
```bash
cd AdminCMS
```

### 3. Проверить подключение к GitHub через SSH
```bash
ssh -T git@github.com
```

### 4. Проверить текущие ветки
```bash
git branch
```

### 5. Создание новой ветки (по задаче)
```bash
git checkout -b feature/название_задачи
```

### 6. Работа с кодом и коммиты
```bash
git add .
git commit -m "Описание задачи"
```

### 7. Отправка изменений на GitHub
```bash
git push -u origin feature/название_задачи
```

---

## Работа с GitHub CLI (если используешь)

### Проверка авторизации
```bash
gh auth status
```

### Авторизация (если не выполнена)
```bash
gh auth login
```

---

## Основной адрес локального проекта:
```
http://localhost:5000/
```

## Путь к проекту на Mac:
```
~/Desktop/serviswork_Core/AdminCMS
```

---

Если возникнут вопросы — обращаться к Геннадию.  
Обновлено: 18.04.2025
