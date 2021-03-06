---
title: How to Install Node Js and Npm on Windows
localeTitle: Как установить Node Js и Npm в Windows
---
## Как установить Node Js и Npm в Windows

Установка Node.js и Npm в Windows очень проста.

Сначала загрузите установщик Windows с [сайта Node.js.](https://nodejs.org/) У вас будет выбор между **LTS** (Long Term Support) или **текущей** версией.

*   **Текущая** версия получает последние функции и обновления быстрее
*   Версия **LTS** foregos изменений функций для повышения стабильности, но получает патчи , такие как исправления и обновление для системы безопасности

После того, как вы выбрали версию, которая соответствует вашим потребностям, запустите программу установки. Следуйте инструкциям, чтобы выбрать путь установки и убедитесь, что функция **диспетчера пакетов npm** включена вместе с **временем выполнения Node.js.** Это должна быть конфигурация по умолчанию.

Перезагрузите компьютер после завершения установки.

Если вы установили конфигурацию по умолчанию, теперь Node.js будет добавлен в ваш PATH. Запустите командную строку или powershell и введите следующие данные для проверки:
```
> node -v 
```

Консоль должна отвечать строкой версии. Повторите процесс для Npm:
```
> npm -v 
```

Если обе команды работают, ваша установка прошла успешно, и вы можете начать использовать Node.js!

#### Дополнительная информация:

Дополнительную информацию и руководства можно найти на [странице документов Node.js.](https://nodejs.org/en/docs/)