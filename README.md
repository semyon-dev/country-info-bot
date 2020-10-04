# CountryInfoBot - Справочник по странам

Бот написан на Python 3.6, для Вконтакте

Версия бота : 1.0

## Что использовалось?
В качестве библиотеки под ВК была выбрана vk_api: `import vk_api` 

Для нахождения информации о странах использовали https://github.com/apilayer/restcountries

Так как ответы json на Английском , для перевода использована YandexTranslate
`from yandex_translate import YandexTranslate`

Для конвертации SVG картинок использовалась API CloudConvert: `import cloudconvert` 

В файле configs.py находятся токены для работы с APIs, но он в .gitignore, поэтому создайте его сами.
