# RecipeChatBot
Распознаёт на фотографии овощ или фрукт и предлагает рецепт с данным ингредиентом.

Проект представляет собой телеграм бота, который распознает на присланной фотографии фрукт или овощ и присылает три рецепта блюд, содержащих распознанный продукт.

Данная программа может пригодиться в ситуации, когда, к примеру, человек стоит в магазине перед товарами и думает, что ему приготовить сегодня на ужиин. Он фотографирует лежащий перед ним овощ или фрукт и получает несколько подходящих вариантов, и ему не нужно прибегать к помощи поисковика и долго перебирать варианты. Либо человек вообще не знает, что за овощ перед ним, и хочет узнать, что это и как его можно приготовить.

Исходные данные для обучения модели были взяты с сайта kaggle.com. Это набор фотографий овощей и фруктов, рассортированных по названиям. Видов продуктов в наборе не очень много, данный набор я использовала для пилотной версии проекта. В будущем планирую найти или собрать данные с большинством имеющихся в продаже фруктов и овощей для более корректной работы программы. Датасет с рецептами был взят с того же сайта и насчитывает более шести тысяч рецептов, из него были убраны столбцы, не несущие полезной информации для данного проекта.

Обучение модели производилось с помощью библиотеки keras.

В будущем можно улучшить программу до распознавания целого набора продуктов на фотографии и предложения рецептов из данного набора. Для этого понадобится гораздо бОльший набор данных для обучения модели. Для пополнения набора рецептов можно будет спарсить новые варианты с кулинарных сайтов. Также планирую после добавить функцию выбора пользователем типа желаемых блюд.

Набор фотографий и все остальные файлы находятся по ссылке: https://drive.google.com/drive/folders/1D2szpOCkHXyj4uFBFLBNZj2u7dYTIuOF?usp=sharing
