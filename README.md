# Best Radio Ultimate 🎵

**Best Radio Ultimate** е модерен desktop плеър за интернет радио, създаден с Python и Tkinter.

## 📥 Инсталация

Изтеглете последната версия от [Releases](https://github.com/KostadinPl/Best-Radio-Ultimate/releases)

## ✨ Характеристики

- 📻 Слушане на интернет радио
- 📁 Организиране на станции в стилове (папки)
- ⭐ Любими станции
- 🔄 Автоматично търсене на ъпдейти
- 🎨 Модерен тъмен интерфейс
- 🖱️ Drag & drop за M3U файлове

## 📝 Конфигурация

Радио станциите се съхраняват във файл `radio_config.json`:

```json
{
  "volume": 100,
  "geometry": "700x800",
  "folders": [
    {
      "name": "Любими",
      "is_favorite": true,
      "stations": [
        ["http://example.com/stream", "Примерна станция⭐"]
      ]
    }
  ]
}
