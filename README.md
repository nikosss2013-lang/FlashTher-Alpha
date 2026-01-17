# FlashTher-Alpha
Rufus-Py (prototype)

Минимальный прототип аналога Rufus на Python (Windows).

Quick start

1) Установите зависимости:

```powershell
python -m pip install -r requirements.txt
```

2) Запустите GUI:

```powershell
python main.py
```

Что реализовано в этом прототипе
- Скаффолд проекта
- Обнаружение съёмных USB-дисков через WMI
- Простая GUI (PySide6) со списком дисков

Дальше: запись образа, форматирование, UEFI/GPT-операции.
