HTTP-код
===

## Поведение

Статус коды:

* `2xx` - запрос успешно обработан
* `4xx` - ошибка, связанная с переданными параметрами
* `5xx` - ошибка сервера, на которую не может повлиять клиент

## Формат ошибок

В случае, если ошибка имеет статус-код не 422, то в теле возрващается пояснение и внутренний код ошибки:

```json
{
    "message": "Bad query parameters",
    "code": 0
}
```

## Статус-коды

* [200](http-code/200.md)
* [201](http-code/201.md)
* [204](http-code/204.md)
* [304](http-code/304.md)
* [400](http-code/400.md)
* [401](http-code/401.md)
* [403](http-code/403.md)
* [404](http-code/404.md)
* [422](http-code/422.md)
* [500](http-code/500.md)
