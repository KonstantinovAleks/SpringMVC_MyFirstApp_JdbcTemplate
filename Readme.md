# video11

### Description of the project
    Проект сделал по видео:
        Alishev -> Spring MVC -> "2. Spring MVC. Первое приложение."
        Alishev -> Spring Mvc -> "3. Spring MVC. Конфигурация с помощью Java кода."
        Alishev -> Spring Mvc -> "4. Spring MVC. Контроллеры. Аннотация @Controller."
        Alishev -> Spring Mvc -> "6. Spring MVC. Параметры GET запроса. Аннотация @RequestParam."
        Alishev -> Spring Mvc -> "8. Spring MVC. CRUD, REST, Паттерн DAO (Data Access Object)."
        Alishev -> Spring Mvc -> "9. Аннотация @ModelAttribute. HTML Формы (Thymeleaf)."
        Alishev -> Spring Mvc -> "10. CRUD приложение. PATCH, DELETE запросы."
        Alishev -> Spring Mvc -> "11. Валидация форм. Аннотация @Valid."

### Entry point
    http://localhost:8080/people

### Сделано
         - отображение списка людей и переход по каждому из них
         - добавление нового человека в список
         - изменение данных человека
         - удаление человека

         - VIDEO11 - проект сделан в новой ветке "video11"
         - добавлена валидация полей, изменения внесены в:
             - pom-файл (добавлена зависимость "hibernate-validator");
             - класс "Person", "PeopleController";
             - new.html-файл, edit.html-файл