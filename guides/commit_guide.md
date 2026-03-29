# Как писать сообщения для коммитов

Общие правила написания сообщений для коммитов:
*   лаконично,
*   однородно,
*   осознанно.

**ВАЖНО:** вписывайте все изменения (ну исключая ну прям совсем мелкие) в коммит. Т.е. пишете: `"Add something. Update this. Delete the thing. Fix some bug."` (только писать надо конкретные вещи, что изменили, подправили или удалили)

---
## Пиши сообщения с заглавной буквы

```text
# Хорошо.
"Add 'get' method to post model"
```

```text
# Плохо.
"add 'get' method to post model"
```

## Не используй прошедшее время

```text
# Хорошо.
"Fix the bug in the function 'set'"
```

```text
# Плохо.
"Fixed bug in the function 'set'"
```

## По возможности указывай на исходный код в сообщении

```text
# Хорошо.
"If applied, this commit will
fix the bug in the function 'set'"
```

```text
# Плохо.
"If applied, this commit will
fix the bug"
```

## Пиши осмысленные сообщения

При написании сообщений для коммитов можно пользоваться формулой:
**«Что сделать + для какой сущности + подробности (необязательно)»**.

```text
# Хорошо.
"Fix a crashed function 'read file'"
"Add function 'get_positive'"
"Add classes, group new fields"
```

```text
# Плохо.
"Fix this"
"Add func"
"Change classes"
```

Больше о коммитах и сообщениях для коммитов узнавай [из документации](#).
