# Field title conflicts with another field

`ERR.DS_API.FIELD.TITLE.CONFLICT`

Конфликт названий полей. Добавленное поле не должно иметь такое же название, как у какого-либо уже существующего поля в датасете.

Проверьте, что у поля уникальное название в рамках датасета.

Возможная причина: поле с таким названием было сначала добавлено в чарт, а потом и в датасет, по которому он построен.
В такой ситуации стоит переименовать поле, добавленное в чарте.