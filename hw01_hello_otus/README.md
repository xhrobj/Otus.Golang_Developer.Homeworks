## Домашнее задание №1 «Hello, OTUS!»

Необходимо написать программу, печатающую в стандартный вывод перевернутую фразу
```
Hello, OTUS!
```

Для переворота строки следует воспользоваться возможностями
[golang.org/x/example/hello/reverse](https://golang.org/x/example/hello/reverse).

Кроме этого необходимо исправить **go.mod** так, чтобы для данного модуля работала
команда `go get`, а полученный **go.sum** закоммитить.

### Критерии оценки
- Пайплайн зелёный - 4 балла
- Используется `reverse.String` - 4 балла
- Понятность и чистота кода - до 2 баллов

#### Зачёт от 7 баллов

### Чек-лист студента ([Что это?](https://github.com/OtusGolang/home_work/wiki/%D0%9A%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B8-%D0%BA-%D1%87%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82%D1%83-%D1%81%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%D0%B0))
- [X] Я перечитал задание после решения. [Зачем перечитывать задание?](https://github.com/OtusGolang/home_work/wiki/%D0%9A%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B8-%D0%BA-%D1%87%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82%D1%83-%D1%81%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%D0%B0#user-content-%D0%97%D0%B0%D1%87%D0%B5%D0%BC-%D0%BF%D0%B5%D1%80%D0%B5%D1%87%D0%B8%D1%82%D1%8B%D0%B2%D0%B0%D1%82%D1%8C-%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5)
- [X] Я запустил `go mod tidy`.
- [X] Я удалил `.sync` файл. [Зачем его удалять?](https://github.com/OtusGolang/home_work/wiki/%5B%D0%A1%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%D0%B0%D0%BC%5D-%D0%9F%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81-%D1%81%D0%B4%D0%B0%D1%87%D0%B8-%D0%94%D0%97#user-content-%D0%92%D0%B0%D1%80%D0%B8%D0%B0%D0%BD%D1%82-2)
- [X] Я использовал `golang.org/x/example/hello/reverse.String()`.
- [X] Я сравнил объем кода с объемом авторского решения. [Зачем сверять объем кода?](https://github.com/OtusGolang/home_work/wiki/%D0%9A%D0%BE%D0%BC%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%80%D0%B8%D0%B8-%D0%BA-%D1%87%D0%B5%D0%BA-%D0%BB%D0%B8%D1%81%D1%82%D1%83-%D1%81%D1%82%D1%83%D0%B4%D0%B5%D0%BD%D1%82%D0%B0#user-content-%D0%97%D0%B0%D1%87%D0%B5%D0%BC-%D1%81%D0%B2%D0%B5%D1%80%D1%8F%D1%82%D1%8C-%D0%BE%D0%B1%D1%8A%D0%B5%D0%BC-%D0%BA%D0%BE%D0%B4%D0%B0)
  - main.go ~12 строк
