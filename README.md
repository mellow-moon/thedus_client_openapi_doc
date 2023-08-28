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
- /inbox
- /inbox/{mail_id}
- /sent
- /sent/{mail_id}
- /spam
```

### /inbox/{mail_id}

```
- /inbox
- /inbox/{mail_id}
- /sent
- /sent/{mail_id}
- /spam
```

### /sent

```
- /inbox
- /inbox/{mail_id}
- /sent
- /sent/{mail_id}
- /spam
```

### /sent/{mail_id}

```
- /inbox
- /inbox/{mail_id}
- /sent
- /sent/{mail_id}
- /spam
```

### /spam

```
- /inbox
- /inbox/{mail_id}
- /sent
- /sent/{mail_id}
- /spam
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
