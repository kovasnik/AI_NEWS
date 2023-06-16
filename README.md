

# AI NEWS


## 📸 Screenshots
||||
|---|---|---|
| ![news](/screenshots/news.jpg) | ![saved](/screenshots/bookmarks.jpg) | ![search](/screenshots/search.jpg) |
| ![news](/screenshots/night_news.jpg) | ![saved](/screenshots/night_bookmarks.jpg) | ![search](/screenshots/night_search.jpg) |
| ![search](/screenshots/site.jpg) | ![search](/screenshots/night_site.jpg) |

## 💡Features

- Світла та темна тема додатку.
- Систему пошуку.
- Можливість відмічати новини.

## ⚙️ Settings

Для налаштування проекту під себе треба сгенерувати свій персональний ключ до NewsAPI, це можна зробити за посиланням [NewsAPI](https://newsapi.org/).

Потім відкрийте свій проект та зайдіть до файлу `gradle.poperties` де ви пропишите свій власний ключ у такій формі:
```
API_KEY = your_api_key
```
Після цього переходите до файлу `Constants.kt` де буде задаватися ваш `COUNTRY_CODE` у такій формі:
```
const val COUNTRY_CODE = "your_country_code", for Ukraine it`s ua, USA - us.

Усі коди країн є за цим посиланням https://newsapi.org/sources .
Також враховуйте що при обирані кодів будь-якої з країн, буде виводитись першочергово інформація з місцевих ресурсів.
```
Виконав кроки вище зробіть rebuild свого проекту.
