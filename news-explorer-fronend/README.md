# ВАЖНО ПРОЧИТАТЬ РЕДМИ

Я попытался максимально смоделировать работу сайта без АПИ, надеюсь того, что сделал - достаточно, ниже по пунктам:

## Про "ничего не найдено"

Если ввести в поиск "Ничего", то выведет секцию "Ничего не найдено"

## Про прелоадер 

Если ввести в поиск "Поиск", то выведет секцию с прелоадером

## Про карточки

Если ввести что-то, то выведет заготовленные мною карточки из data.js. Так же некоторое количество карточек я сделал "сохраненными", их будет видно на странице /saved-news

## Про авторизацию/Регистрацию

1. В файле App.js есть стэйт isLogin, его значение по умолчанию - false, можно поменять на true и будет выполнена авторизация;
2. В целом если пройти регистрацию/авторизацию, то стейт сам поменяется, а в консоли выдаст уведомление о регистрации/авторизации (и пока на этом все), так же имя решил оставить тоже одно пока;

## Планы:

1. Написать внятное "Об Авторе", сейчас что-то грустно выглядит :(
2. Переписать валидацию, сделав общий компонент для форм (сейчас работает, но хочется по-другому)
