# TForceReply

- **class** `TForceReply` (`telegram\object\markup\TForceReply`) **extends** [`AbstractMarkup`](classes/telegram/object/markup/AbstractMarkup.md)
- **source** `telegram/object/markup/TForceReply.php`

**Description**

Shows reply interface to the user, as if they manually selected the bot‘s message and tapped 'Reply'

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