# TReplyKeyboard

- **class** `TReplyKeyboard` (`telegram\object\markup\TReplyKeyboard`) **extends** [`AbstractMarkup`](classes/telegram/object/markup/AbstractMarkup.md)
- **source** `telegram/object/markup/TReplyKeyboard.php`

**Child Classes**

> [TInlineKeyboard](classes/telegram/object/markup/TInlineKeyboard.md)

**Description**

This object represents a custom keyboard with reply options


---

#### Properties

- `->`[`params`](#prop-params) : `array`
- `->`[`buttons`](#prop-buttons) : `array` - _Кнопки_
- `->`[`row`](#prop-row) : `int` - _Указатель текущей строки в кнопках_
- *See also in the parent class* [AbstractMarkup](classes/telegram/object/markup/AbstractMarkup.md).

---

#### Methods

- `->`[`__construct()`](#method-__construct)
- `->`[`row()`](#method-row) - _Добавить новую строку в панель кнопок_
- `->`[`button()`](#method-button) - _Добавить кнопку_
- `->`[`setResize()`](#method-setresize) - _Указывает клиенту подогнать высоту клавиатуры под количество кнопок_
- `->`[`setOneTime()`](#method-setonetime) - _Указывает клиенту скрыть клавиатуру после использования (после нажатия на кнопку)._
- `->`[`setSelective()`](#method-setselective)
- `->`[`getMarkup()`](#method-getmarkup)
- See also in the parent class [AbstractMarkup](classes/telegram/object/markup/AbstractMarkup.md)

---
# Methods

<a name="method-__construct"></a>

### __construct()
```php
__construct(array $params): void
```

---

<a name="method-row"></a>

### row()
```php
row(): TReplyKeyboard
```
Добавить новую строку в панель кнопок

---

<a name="method-button"></a>

### button()
```php
button(string $text): TReplyKeyboard
```
Добавить кнопку

---

<a name="method-setresize"></a>

### setResize()
```php
setResize(bool $value): TReplyKeyboard
```
Указывает клиенту подогнать высоту клавиатуры под количество кнопок
(сделать её меньше, если кнопок мало и наоборот)

---

<a name="method-setonetime"></a>

### setOneTime()
```php
setOneTime(bool $value): TReplyKeyboard
```
Указывает клиенту скрыть клавиатуру после использования (после нажатия на кнопку).
Её по-прежнему можно будет открыть через иконку в поле ввода сообщения.

---

<a name="method-setselective"></a>

### setSelective()
```php
setSelective(bool $value): TReplyKeyboard
```

---

<a name="method-getmarkup"></a>

### getMarkup()
```php
getMarkup(): array
```