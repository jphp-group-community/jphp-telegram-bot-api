# TReplyKeyboardRemove

- **class** `TReplyKeyboardRemove` (`telegram\object\markup\TReplyKeyboardRemove`) **extends** [`AbstractMarkup`](classes/telegram/object/markup/AbstractMarkup.md)
- **source** `telegram/object/markup/TReplyKeyboardRemove.php`

**Description**

Upon receiving a message with this object, Telegram clients will remove the current custom keyboard and display the default letter-keyboard. By default, custom keyboards are displayed until a new keyboard is sent by a bot. An exception is made for one-time keyboards that are hidden immediately after the user presses a button

---

#### Methods

- `->`[`__construct()`](#method-__construct)
- `->`[`setSelective()`](#method-setselective) - _Use this parameter if you want to force reply from specific users only. Targets: 1) users that are @mentioned in the text of the Message object; 2) if the bot's message is a reply (has reply_to_message_id), sender of the original message._
- See also in the parent class [AbstractMarkup](classes/telegram/object/markup/AbstractMarkup.md)

---
# Methods

<a name="method-__construct"></a>

### __construct()
```php
__construct(): void
```

---

<a name="method-setselective"></a>

### setSelective()
```php
setSelective(bool $value): void
```
Use this parameter if you want to force reply from specific users only. Targets: 1) users that are @mentioned in the text of the Message object; 2) if the bot's message is a reply (has reply_to_message_id), sender of the original message.