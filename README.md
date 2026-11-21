# 🛡️ AyuScamDB

![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge)
![Security](https://img.shields.io/badge/Research-AntiScam-red?style=for-the-badge)

**AyuScamDB** — открытая база расследований мошеннических сайтов, фишинговых ресурсов и интернет-угроз.

> Каждый сайт — отдельное расследование.

---

## 🔎 Searches

| ID | Сайт | Тип угрозы | Отчёт |
|---|---|---|---|
| 0001 | `xchna[.]store` | Fake МВД / Scareware | [Report](searchs/0001/report.md) |
| 0002 | `ralqero[.]com` | Подозрительный платёжный ресурс | [Report](searchs/0002/report.md) |

---

## 📁 Structure

```text
AyuScamDB/
├── searchs/
│   ├── 0001/
│   │   ├── report.md
│   │   ├── domains.txt
│   │   ├── hashes.txt
│   │   └── screenshots/
│   └── 0002/
│       └── report.md
├── README.md
└── LICENSE
```

## 📑 Reports

Каждое расследование может содержать:

- Информацию о домене.
- Описание мошеннической схемы.
- Результаты технического анализа.
- Скриншоты и доказательства.
- Индикаторы угроз.
- Контрольные суммы файлов.

## 🚨 Report a Scam

Нашли мошеннический сайт?

Создайте новый Issue в данном репозитории, указав подозрительный домен и описание угрозы.

## ⚠️ Disclaimer

Материалы публикуются исключительно в исследовательских и образовательных целях. Опасные ссылки обезврежены. Рабочие мошеннические шаблоны и вредоносное ПО не распространяются.

---

**Developer:** AyuRage

**License:** Apache 2.0

**© 2026 AyuScamDB**
