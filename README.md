# 📊 March-projects

Коллекция ноутбуков и CSV-файлов для практики визуализации данных, анализа временных рядов и работы с библиотеками `pandas`, `matplotlib`, `seaborn` и другими.

## 📁 Структура проекта

```zsh
 .
├──  app
│   ├──  project_3.2
│   │   ├──  iris.csv
│   │   ├──  main.ipynb
│   │   └──  'Визуализация (Блокнот к вебинару).ipynb'
│   ├──  project_3.3
│   │   ├──  main.ipynb
│   │   ├──  train.csv
│   │   ├──  Визуализация_2_Seaborn.ipynb
│   │   └──  Визуализация_3.ipynb
│   └──  project_3.5
│       ├──  main.ipynb
│       └──  Временные_ряды.ipynb
├──  pyproject.toml
├── 󰂺 README.md
└──  uv.lock
```

## ⚙️ Установка зависимостей

Убедитесь, что у вас установлен [Python 3.10+](https://www.python.org/) или `uv`.

Устанавливайте uv с помощью наших автономных установщиков:

```bash
# В macOS и Linux.
curl -LsSf https://astral.sh/uv/install.sh | sh
```

```bash
# В Windows.
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Установка всех зависимостей:

```bash
uv sync && source .venv/bin/activate  # или uv sync; .\.venv\Scripts\Activate.ps1; на Windows
```

Если используете pip то просто запустите юпитер ноутбук

## 🧠 Используемые технологии

- Python 🐍
- Pandas 📊
- Matplotlib 🎨
- Seaborn 🌊
- Jupyter Notebooks 📓
