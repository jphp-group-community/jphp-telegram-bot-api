## telegram-bot-api
> version 1.1.0, created by JPPM.


### Install
```
jppm add telegram-bot-api@1.1.0
```

### API
**Classes**

#### `telegram\exception`

- [`TelegramError`](classes/telegram/exception/TelegramError.md)
- [`TelegramException`](classes/telegram/exception/TelegramException.md)

#### `telegram\object\markup`

- [`AbstractMarkup`](classes/telegram/object/markup/AbstractMarkup.md)
- [`TForceReply`](classes/telegram/object/markup/TForceReply.md)- _Shows reply interface to the user, as if they manually selected the bot‘s message and tapped 'Reply'_
- [`TInlineKeyboard`](classes/telegram/object/markup/TInlineKeyboard.md)- _This object represents an inline keyboard that appears right next to the message it belongs to._
- [`TReplyKeyboard`](classes/telegram/object/markup/TReplyKeyboard.md)- _This object represents a custom keyboard with reply options_
- [`TReplyKeyboardRemove`](classes/telegram/object/markup/TReplyKeyboardRemove.md)- _Upon receiving a message with this object, Telegram clients will remove the current custom keyboard and display the default letter-keyboard. By default, custom keyboards are displayed until a new keyboard is sent by a bot. An exception is made for one-time keyboards that are hidden immediately after the user presses a button_

#### `telegram\object`

- [`TAudio`](classes/telegram/object/TAudio.md)
- [`TChat`](classes/telegram/object/TChat.md)
- [`TContact`](classes/telegram/object/TContact.md)
- [`TDocument`](classes/telegram/object/TDocument.md)
- [`TFile`](classes/telegram/object/TFile.md)
- [`TLocation`](classes/telegram/object/TLocation.md)
- [`TMarkup`](classes/telegram/object/TMarkup.md)
- [`TMessage`](classes/telegram/object/TMessage.md)
- [`TMessageEntity`](classes/telegram/object/TMessageEntity.md)
- [`TPhotoSize`](classes/telegram/object/TPhotoSize.md)
- [`TSticker`](classes/telegram/object/TSticker.md)
- [`TUpdate`](classes/telegram/object/TUpdate.md)
- [`TUser`](classes/telegram/object/TUser.md)
- [`TUserProfilePhotos`](classes/telegram/object/TUserProfilePhotos.md)
- [`TVenue`](classes/telegram/object/TVenue.md)
- [`TVideo`](classes/telegram/object/TVideo.md)
- [`TVoice`](classes/telegram/object/TVoice.md)

#### `telegram\query`

- [`TAnswerCallbackQuery`](classes/telegram/query/TAnswerCallbackQuery.md)- _Use this method to send answers to callback queries sent from inline keyboards. The answer will be displayed to the user as a notification at the top of the chat screen or as an alert. On success, True is returned._
- [`TBaseQuery`](classes/telegram/query/TBaseQuery.md)
- [`TEditMessageTextQuery`](classes/telegram/query/TEditMessageTextQuery.md)
- [`TForwardMessageQuery`](classes/telegram/query/TForwardMessageQuery.md)
- [`TGetFileQuery`](classes/telegram/query/TGetFileQuery.md)
- [`TGetMeQuery`](classes/telegram/query/TGetMeQuery.md)
- [`TGetUpdatesQuery`](classes/telegram/query/TGetUpdatesQuery.md)
- [`TGetUserProfilePhotosQuery`](classes/telegram/query/TGetUserProfilePhotosQuery.md)
- [`TKickChatMemberQuery`](classes/telegram/query/TKickChatMemberQuery.md)
- [`TSendAudioQuery`](classes/telegram/query/TSendAudioQuery.md)
- [`TSendChatActionQuery`](classes/telegram/query/TSendChatActionQuery.md)
- [`TSendContactQuery`](classes/telegram/query/TSendContactQuery.md)
- [`TSendDocumentQuery`](classes/telegram/query/TSendDocumentQuery.md)
- [`TSendLocationQuery`](classes/telegram/query/TSendLocationQuery.md)
- [`TSendMessageQuery`](classes/telegram/query/TSendMessageQuery.md)
- [`TSendPhotoQuery`](classes/telegram/query/TSendPhotoQuery.md)
- [`TSendStickerQuery`](classes/telegram/query/TSendStickerQuery.md)
- [`TSendVenueQuery`](classes/telegram/query/TSendVenueQuery.md)
- [`TSendVideoQuery`](classes/telegram/query/TSendVideoQuery.md)
- [`TSendVoiceQuery`](classes/telegram/query/TSendVoiceQuery.md)
- [`TUnbanChatMemberQuery`](classes/telegram/query/TUnbanChatMemberQuery.md)

#### `telegram`

- [`TelegramBotApi`](classes/telegram/TelegramBotApi.md)

#### `telegram\tools`

- [`TUpdateListener`](classes/telegram/tools/TUpdateListener.md)