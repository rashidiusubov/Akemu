# Akemu

![image](https://github.com/user-attachments/assets/a92d0d72-326f-44c9-817f-39cd0b398524)

## Общее описание
Akemu — это простое приложение на Python с графическим интерфейсом на основе `customtkinter`, которое отслеживает содержимое буфера обмена и автоматически воспроизводит текст из буфера обмена в текстовые поля других приложений. Также приложение позволяет запускать действия по горячей клавише и поддерживает таймер для автоматической вставки текста.

## Функции и настройки

- **Буфер обмена**: Отображает содержимое буфера обмена и отслеживает его изменения.
- **Обратный отсчёт**: После нажатия кнопки "Начать" запускается трёхсекундный обратный отсчёт перед воспроизведением текста.
- **Печать текста**: Воспроизводит текст из буфера обмена с небольшими задержками между символами. Воспроизведение текста можно прервать нажатием клавиши `p`.
- **Горячая клавиша**: Приложение поддерживает горячую клавишу `Ctrl + B` для запуска печати текста.
  
## Команды для сборки и запуска

### Клонирование репозитория:

```bash
git clone https://github.com/Rashid-Yusubov/Akemu.git
cd Akemu
```

### Установка необходимых библиотек:

```bash
pip install -r requirements.txt
```

### Запуск проекта:
```bash
python akemu.py
```
