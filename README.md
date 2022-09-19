# Контрольная работа.

## Задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3-м символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
### Пример:

["hello", "2", "world",";"] -> ["2",";"]

### Описание алгоритма решения:
Объявляется два массива, одиноковой длинны. Далее запускаем цикл проверки условия (<=3), если да, заносим элемент первого массива в count элемент второго массива. Переменная count нужна чтобы поочередно без пробелов закидывать элемент из первого массива во второй, без пробелов. После присвоения увеличиваем переменную count на 1 и возвращаемся к циклу for, в котором увеличилось i на 1. И так проверяем до конца. 

# Схема
![Схема](Scrinshot.PNG)
ссылка на [схему](https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B0%20%D0%B1%D0%B5%D0%B7%20%D0%BD%D0%B0%D0%B7%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F.drawio#R1Vlbb9owFP41SNvDqjgXLo%2BjsO2hqyp109q%2BGWIST0kcGVOgv37H2LkaSrqGQKVKtU%2FOSXx8vs%2FfSeg51%2FHmO8dp%2BJP5JOrZlr%2FpOZOebaPhcAD%2FpGWrLH1vpAwBp752Kgz39IVoo6WtK%2BqTZcVRMBYJmlaNc5YkZC4qNsw5W1fdFiyqPjXFATEM93McmdY%2F1Behsg7tQWH%2FQWgQZk9GfZ1fjDNnnckyxD5bl0zOtOdcc8aEGsWbaxLJzcv2RcV9O3A1XxgniWgS8LT%2B%2FYQettvHcfCH%2FZq90Buy%2BmLrtYltljDxIX89ZVyELGAJjqaFdczZKvGJvKsFs8LnhrEUjAiMf4kQW11MvBIMTKGII30VFsy3DzL%2Bysumj%2BVrk42%2BuZpts9mGilIYzPIoGBdBcpLFqPxkUge3TZuWbMXn5JW9Qq7GH%2BYBEa84Onl1gRaExQSSgDhOIizoc3UhWOMzyP3y0DtGYYm2pbnkIo0szSTUt6q3UOvSUWUgHLuRVbuR2gnjRjAo5VOYdjh7A%2Ba8S8KcdQRzLeLHaQgfhDrBjz1shp%2B2yq7Tf8bRSqewFJwmQc8b97wJnNVYJglp9SPYnfGMwyiQo7KbOtV3nrbpqfKdA1bk%2F91DMmyX0AYHcSqHUEMcRSRiAccxRKeEU0iS8Pq1u%2BLCeB1SQe5TvKv0GjSvCrMF3ZBMxeTcpxxUibJEepOlyBH1TLggm9cxZUJABzh2jcGeznJdSBTKyhuW5GlgHUZNpd5vLe7wI3H63DqS9THHDoJBJ%2BeAU9eREx%2F%2FWWdXOggeocP7QPhpEQuDhlAYvRMK7yI38oyK3bLzFqxSrqJ6l1OwdkT8q9a6zCGVpFwe5rY9qnLbdb1XW8G6v1N9h4CBWkGrB8DAQBNdwPxTqQWwQO0pyP3VDUmkeMll9XEsxXYn%2BRDmfDYQyEMWz1bL4yrdhgTXTlEXmRKcNx%2BdSDDqXxIl7Q45OeqUkyaJBjUSoWaN9ZvJ7VSf4w2PkLvm71he7%2BTkHhnkLvXrktaqO9918qpBL2ivOG%2B29XlDb493f3XaVzDcPfU9z2tG%2FXqj1R71z9J%2Bt8jgxi0xem9P%2FL59Rga6F4xL7VLEo6W3Trk%2FylBRrhztmbRlfhLaeyTtzNi2Rw1l7XTYdi5J1jpUNWQ35YR7EllzvCoU6o3LiT8XZemXuHYPjxQmGqKIpkvSCT2QVZdUgx3I3sOO%2Bqe29tjhmrtE5izxdXNx7uPErXXJe%2FbL7fI0sc2PDx9dOhu%2FkZ73G4L51nfH1XlTahAPfKn12XwV73bmGGZnqjI3sxZB7NVeknM2n4%2F1Zpc9vZ2c9WSsb5K775P0vk36D6rDtPjZVOlN8eOzM%2F0H)

Программа с решением находится в папке *zadanie*