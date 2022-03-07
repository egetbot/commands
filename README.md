# Egetbot commands

У большинства команд есть небольшая подсказка по использованию, достаточно отправить в чат команду без каких-либо параметров.



## Общее:
#### !bot
- проверка что бот функционирует
#### !commands
- ссылка на эту страницу



## Антиспам команды:
> Помимо указанных ниже команд у бота есть встроенные фильтры антиспама. По-умолчанию включены. Если необходимо отключить Антиспам или какой-то отдельный фильтр, то пишите мне в [лс](https://www.twitch.tv/egetvitchdd).
#### !notbot @username
- разбанивает пользователя если сработал Антиспам и добавляет его в исключения.
#### !mt [текст]
- проходит по последним сообщениям и удаляет сообщения с указанным текстом.
#### !dlm [on|off|число]
- ограничивает длину сообщения, **число** - в диапазоне от 150 до 500,   
сообщения превысившие указанноую длину удаляются,   
выдает таймаут на 30 секунд, при повторных срабатываниях - 120, 240 секунд.   



## AutoMod твича:

#### !addbt [текст]
- добавляет указанный текст в Блок-лист AutoMod'а
> Примичание: ***НЕ Добавляйте БАНВОРДЫ*** через эту команду
#### !delbt [текст]
- удаляет указанный текст из Блок-листа AutoMod'а
> Примичание: на данный момент удаляет толкьо текст добавленный через бота

   
## Взаимодействие с чатом:

#### !ecmd [add|del|edit] [названиеКоманды] [текст]
- добавляет "команду", которой можно проспамить соцсети или pr-ссылки,   
команда срабатывает *только* с указанием количества повторений,   
но не более 20 повторений за одно использование команды.
  - Пример:
    > !ecmd add тест привет   
  - Использование:   
    > !тест 1   
  - Результат:   
    > отправит в чат одно соощение с текстом "привет"   
#### !elinks
- показывает все команды добавленные через команду !ecmd


## Обратная связь:
По любым вопросам пишите в лс твича.

by [Egetvitchdd](https://www.twitch.tv/egetvitchdd) | 2022.03.08
