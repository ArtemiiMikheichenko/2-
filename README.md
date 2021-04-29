# Задача 1 🃏
Напишите программу, которая должна имитировать раздачу карт для игры в покер. Программа получает число n, задаваемое с консоли пользователем, и раздает карты на n игроков (по 5 карт каждому) из рассортированной колоды. Разделяйте пять карт, выданных каждому игроку, пустой строкой. Объект карты реализуется классом PlayingCard.

Комментарии
Для инициализации колоды карт задействуются статические поля SUITS_LIST и RANK_LIST класса PlayingCard.
Перед раздачей колоду необходимо перемешать. Задействуйте класс Random.
Программа должна валидировать вводимое количество игроков и при необходимости выводить сообщение об ошибке.

Задача 2 🧗
Скалолазы двигаются по прямому маршруту. На пути им встречаются возвышенности и впадины. Их маршрут может быть представлен целочисленным одномерным массивом, в котором каждая ячейка хранит информацию об одном препятствии. Каждый скалолаз имеет разные возможности по преодолению маршрута, к которым относятся: максимальная высота возвышенности которую он сможет преодолеть, высота перепада трех ближайших препятствий и продолжительность маршрута. Написать программу создающую случайный маршрут для скалолаза по его возможностям.

Комментарии
Вывод массива должен быть реализован по примеру представленному в комментарии класса RockExample.
Возможности скалолаза задаются из консоли.
