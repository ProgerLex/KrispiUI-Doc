<div align="center">
# ➜ KRISPI UI
 
**Библиотека GUI-меню для Roblox**
 
`v2.1` · `stable` · `Roblox / Luau`
 
</div>
---
 
## 📋 О библиотеке
 
**KRISPI UI** — лёгкая и пастельная библиотека для создания GUI-меню в Roblox. Простой API, готовые компоненты и минимум кода для запуска.
 
## 🚀 Быстрый старт
 
```lua
local UI = loadstring(game:HttpGet("https://pastebin.com/raw/qzxqAR0a"))()
 
local win = UI:CreateWindow("Моё меню")
local main = win:CreateTab("Главная")
 
main:CreateButton("Привет", function()
    print("Привет!")
end)
```
 
## ✨ Компоненты
 
| Компонент | Описание |
|---|---|
| `CreateWindow` | Создаёт главное окно интерфейса |
| `CreateTab` | Добавляет вкладку в окно |
| `CreateSection` | Разделитель-заголовок внутри вкладки |
| `CreateButton` | Кнопка с колбэком |
| `CreateToggle` | Переключатель вкл/выкл |
| `CreateSlider` | Числовой слайдер с диапазоном |
| `CreateDropdown` | Выпадающий список опций |
 
## 📄 Лицензия
 
Распространяется свободно. Используйте на своё усмотрение.
 
---
 
<div align="center">
<sub>➜ KRISPI UI · v2.1 · Сделано с душой</sub>
</div>
