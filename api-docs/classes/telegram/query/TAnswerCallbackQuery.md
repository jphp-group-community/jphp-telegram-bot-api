# TAnswerCallbackQuery

- **class** `TAnswerCallbackQuery` (`telegram\query\TAnswerCallbackQuery`) **extends** [`TBaseQuery`](classes/telegram/query/TBaseQuery.md)
- **source** `telegram/query/TAnswerCallbackQuery.php`

**Description**

Use this method to send answers to callback queries sent from inline keyboards. The answer will be displayed to the user as a notification at the top of the chat screen or as an alert. On success, True is returned.


---

#### Methods

- `->`[`__construct()`](#method-__construct)
- `->`[`callback_query_id()`](#method-callback_query_id) - _Unique identifier for the query to be answered_
- `->`[`text()`](#method-text) - _Text of the notification. If not specified, nothing will be shown to the user, 0-200 characters_
- `->`[`url()`](#method-url) - _URL that will be opened by the user's client._
- `->`[`show_alert()`](#method-show_alert) - _If true, an alert will be shown by the client instead of a notification at the top of the chat screen. Defaults to false._
- `->`[`cache_time()`](#method-cache_time) - _The maximum amount of time in seconds that the result of the callback query may be cached client-side. Telegram apps will support caching starting in version 3.14. Defaults to 0._
- See also in the parent class [TBaseQuery](classes/telegram/query/TBaseQuery.md)

---
# Methods

<a name="method-__construct"></a>

### __construct()
```php
__construct(telegram\TelegramBotApi $api): void
```

---

<a name="method-callback_query_id"></a>

### callback_query_id()
```php
callback_query_id(string $value): TAnswerCallbackQuery
```
Unique identifier for the query to be answered

---

<a name="method-text"></a>

### text()
```php
text(string $value): TAnswerCallbackQuery
```
Text of the notification. If not specified, nothing will be shown to the user, 0-200 characters

---

<a name="method-url"></a>

### url()
```php
url(string $value): TAnswerCallbackQuery
```
URL that will be opened by the user's client.

---

<a name="method-show_alert"></a>

### show_alert()
```php
show_alert(string $value): TAnswerCallbackQuery
```
If true, an alert will be shown by the client instead of a notification at the top of the chat screen. Defaults to false.

---

<a name="method-cache_time"></a>

### cache_time()
```php
cache_time(string $value): TAnswerCallbackQuery
```
The maximum amount of time in seconds that the result of the callback query may be cached client-side. Telegram apps will support caching starting in version 3.14. Defaults to 0.