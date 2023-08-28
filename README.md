# OpenAPI документация к почтовому сервису Thedus.

Это документация к почтовому сервису Thedus. Сервис позволяет просматривать и управлять отправленными, входящими письмами, а также письмами, помеченными как спам.

## Конечные точки

```
- /inbox
- /inbox/{mail_id}
- /sent
- /sent/{mail_id}
- /spam
```

## Методы

### /inbox

```
- GET
- DELETE
```

### /inbox/{mail_id}

```
- GET
- DELETE
```

### /sent

```
- GET
- POST
- DELETE
```

### /sent/{mail_id}

```
- GET
- DELETE
```

### /spam

```
- GET
- DELETE
```

## Компоненты

```
- Mail
- Inbox
- Sent
- Spam
- Error
```

## Аутентификация

```
securitySchemes:
    ApiKeyAuth:
      type: apiKey
      in: header
      name: KEY
```
