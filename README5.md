# 📘 Модуль 4.2: Декоративні елементи

## 📍 Позиціонування

- `position`: `static` | `relative` | `absolute` | `fixed` | `sticky`  
- `z-index`

---

## 🎬 CSS-переходи

- `transition-property`: `<властивість>` | `color`, `background-color`  
- `transition-duration`: `<час>` | `2s` | `0.5s` | `2000ms` | `500ms`  
- `transition-timing-function`: `<функція розподілу часу>` | `ease`, `linear`, `ease-in`, `ease-out`, `ease-in-out`  
- `transition-delay`: `<затримка>`

- `transition`: `[property] [duration] [timing-function] [delay]`  
- `transition`: `background-color 500ms linear, transform 500ms ease-in-out;`

### Властивість `transition-timing-function`

- `ease` — перехід починається повільно, швидко прискорюється, а потім знову сповільнюється в кінці.  
- `linear` — перехід має рівномірну швидкість.  
- `ease-in` — починається повільно, швидкість переходу збільшується до повного завершення переходу.  
- `ease-out` — починається швидко, уповільнюється протягом переходу.  
- `ease-in-out` — починається повільно, прискорюється, а потім знову сповільнюється.

---

## 🌀 2D-трансформації

- `transform`: `none` | `<тип трансформації>` `<тип трансформації>` ...  
- `transform: scale(1.15)` — маштабування  
- `transform: rotate(45deg)` — прокручування  
- `transform: translate(100px, 200px)` — зміщення  
- `transform: translate(-50%, -50%)` — центрування елемента  
- `transform: skew(30deg)` — викривлення

---

## 🧙‍♀️ Псевдоелементи

Використання:  
`.box::before`, `.box::after`, `.box:hover::before`

---

## 🔹 Додаткові ресурси 📚
- 🖼 [cubic-bezier](https://cubic-bezier.com/#.17,.67,.83,.67) – сервіс генератор анімації   