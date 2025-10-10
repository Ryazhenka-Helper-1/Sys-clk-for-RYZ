# ⚙️ Sys-clk for RYZ (RYZ-Toolbox)

> 🎮 Кастомная версия sys-clk от **Kirill-git**  
> 🧪 Управление частотами CPU/GPU/MEM на Nintendo Switch™

[![Downloads](https://img.shields.io/github/downloads/Ryazhenka-Helper-1/Sys-clk-for-RYZ/total?style=for-the-badge&logo=github&color=4ecdc4)](https://github.com/Ryazhenka-Helper-1/Sys-clk-for-RYZ/releases)
[![Latest Release](https://img.shields.io/github/v/release/Dimasick-git/Ryzhenka?style=for-the-badge&logo=github&color=ff6b6b)](https://github.com/Dimasick-git/Ryzhenka/releases/latest)
[![License](https://img.shields.io/badge/license-GPLv3-blue?style=for-the-badge)](https://github.com/Dimasick-git/Ryzhenka/blob/main/LICENSE)

---

## 📖 Описание

**Sys-clk for RYZ** — это форк оригинального sys-clk, адаптированный под Ryazhenka-экосистему.  
Создан исключительно в образовательных целях и для тестирования производительности.

> ⚠️ Используйте на свой страх и риск. Это инструмент для опытных пользователей.

---

## ✨ Особенности

- 🔧 **Управление частотами**: CPU / GPU / MEM — динамически и вручную  
- 🎮 **Профили для игр**: автоматическое применение по title_id  
- 📊 **Мониторинг в реальном времени**: частоты, температура, заряд  
- 🧩 **Интеграция с Tesla**: быстрый доступ через overlay

---

## 🚀 Установка

1. Скачайте релиз [v5.0.0](https://github.com/Dimasick-git/Ryzhenka/releases/tag/v5.0.0)  
2. Распакуйте архив в корень SD-карты  
3. Убедитесь, что установлены:
   - Atmosphère (последняя версия)  
   - Tesla Menu (если нужен overlay)  
4. Перезапустите консоль

---

## 🕹️ Использование через Tesla Overlay (рекомендуется)

1. Удерживайте **L + R + D-Pad Вверх** одновременно  
2. Откроется меню Tesla  
3. Выберите `sys-clk` и настройте:
   - Просмотр текущих частот и температуры  
   - Переключение профилей: Handheld / Docked / Charging  
   - Ручная настройка CPU / GPU / MEM

---

## 🧾 Конфигурация вручную

Файл: `config/sys-clk/config.ini`  
Пример настройки для конкретной игры:

```ini
[01006A800016E000]
docked_cpu=1785
docked_gpu=921
handheld_charging_gpu=460

Поддерживаемые частоты (МГц)

 CPU GPU MEM (EMC)
Min 1020 76 1331
Max 1785 921 1600

Примечание: Не все частоты могут быть стабильны на всех консолях.

Предупреждение / Ограничение ответственности

· Авторы оригинального sys-clk НЕ НЕСУТ ОТВЕТСТВЕННОСТИ за этот форк.
· Использование этого ПО может привести к нестабильности работы, потере данных или повреждению оборудования.
· Некорректные настройки частот могут привести к перегреву или другим проблемам.
· Это инструмент для энтузиастов. Используйте его, только если понимаете, что делаете.

Благодарности

· Команда retronx-team за оригинальный проект sys-clk.
· Сообщество энтузиастов Nintendo Switch.

Лицензия

Этот проект распространяется под лицензией GPLv3. Полный текст лицензии доступен в файле LICENSE.

---

Последняя версия: v5.0.0 | Скачать релиз
