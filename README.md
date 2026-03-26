# ua-urban-schema
JSON Schema for validation of Ukrainian urban planning data (Order #56)
# 🗺️ UA-Urban-Schema (v1.0)

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![JSON Schema](https://img.shields.io/badge/Schema-JSON%20Schema%202020--12-orange)](https://json-schema.org/)
[![Status: v1.0-Release-Candidate](https://img.shields.io/badge/Status-v1.0--RC-green)](#)

---

### 🇺🇦 Українською

**Машиночитана специфікація містобудівних даних України.** Реалізація вимог **Наказу Мінрегіону №56 від 22.02.2022** у форматі JSON Schema.

#### 🚀 Призначення
Цей проект створений для автоматизації контролю якості ГІС-даних містобудівного кадастру. Він дозволяє миттєво перевірити GeoJSON файли на відповідність державним стандартам.

* **Валідація атрибутів:** Перевірка кодів КАТОТТГ, назв та типів об'єктів.
* **Геометрична чистота:** Підтримка 2D/3D (Z-координати) для інженерних мереж.
* **Модульність:** Використання `common.json` для базових геотипів.

#### 🛠️ Як використовувати
[Плагін json_ua для QGIS](https://github.com/krechkivsky/json_ua)

---

### 🇬🇧 In English

**Machine-readable specification for Ukrainian urban planning data.** Implementation of the **Order of the Ministry of Regional Development №56 (dated 22.02.2022)** in JSON Schema format.

#### 🚀 Purpose
This project is designed to automate quality control for Urban Planning Cadastre GIS data. It enables instant validation of GeoJSON files against national standards.

* **Attribute Validation:** Checks for KATOTTG codes, object names, and classifications.
* **Geometric Integrity:** Full support for 2D/3D (Z-coordinates) for utility networks.
* **Modularity:** Uses `common.json` for reusable spatial data types.

#### 🛠️ Usage
[QGIS Plugin json_ua](https://github.com/krechkivsky/json_ua)

---

## 📂 Repository Structure / Структура репозиторію

* `schema.json` — The main validation entry point / Головна точка валідації.
* `common.json` — Base types and spatial definitions / Базові типи та просторові визначення.
* `examples/` — Sample files (Valid/Invalid) / Приклади файлів.

## 🤝 Contributing / Співпраця
Contributions to the schema development are welcome, especially regarding **CityGML** and **GML 3.0** integration.  
*Запрошую до співпраці, особливо в частині інтеграції з CityGML та GML 3.0.*

## ⚖️ License / Ліцензія
This project is licensed under the **GNU GPL v3.0**.  
Author: **Mykhailo Krechkivski** (Senior GIS Architect).
