## Лабораторна робота 4

### Опис
У цій роботі клієнт і сервер реалізують ті ж базові команди (ping, echo, login, msg, list, exit),  
але додано обмін файлами через команду `file <user> <filename>`.

### Файли
- `server.js` — TCP-сервер на порту 3008
- `client.js` — TCP-клієнт з консольною UI

### Запуск

1. У терміналі A запустіть сервер:
   node server.js
2. У терміналі B — клієнт:
    node client.js
3. У клієнті вводьте:
    login `yourName`
    ping
    echo Hello
    list
    msg `user` `text`
    file `user` `path/to/file`
    exit