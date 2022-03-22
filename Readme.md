## Hello world - SpringMVC & Thymeleaf
### Описание
Программа выводит приветствие пользователя, переданного в контроллер с помощью параметров GET запроса.

### Предварительные настройки
Необходимо установить TomCat server. Настройки сервера лежат в классе SpringConfig implements WebMvcConfigurer.

### Использование
Get
```http://localhost:8080/hello?name=Mike&surname=Tyson```

ResponseBody
```Hello world!!!Hello Mike Tyson```