# Axiom Verge 2 — українська локалізація

## Windows 64-bit: встановлення без додаткового ПЗ

[Завантажити готовий ZIP](https://github.com/SmailWolf/AxiomVerge2-UA/releases/download/v1.1.0/AxiomVerge2-UA-Windows-1click-v1.1.0.zip).

1. Завантаж ZIP і повністю розпакуй його.
2. Двічі клацни Install-AxiomVerge2-UA.bat.
3. Вибери папку гри з AxiomVerge2.exe і підтверди встановлення.

Окремо встановлювати Node.js або Python та підключатися до інтернету не потрібно. ZIP містить переносні версії потрібних компонентів. Файл .bat запускає сценарій .ps1 у Windows PowerShell; обидва призначені для Windows. Оригінали зберігаються в UA-localization-backup. Щоб відновити їх, запусти Restore-AxiomVerge2-UA.bat.

Файли самої гри не розповсюджуються. Патчер підтримує лише версію, вказану в supported-version.json; для іншої версії він зупиниться без заміни файлів.

## Linux

Windows .bat і .ps1 файли в Linux не запускаються. Для Linux потрібні Node.js, Python 3 і pip. Із папки вихідного проєкту виконай:

```sh
python3 -m pip install --user -r requirements.txt
python3 install.py '/шлях/до/Axiom Verge 2'
```

## Статус

Переклад охоплює 1 215 записів; повне проходження для редакторської вичитки не виконано. Новий Windows ZIP з переносними компонентами ще не сканувався VirusTotal.
