# video14

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
        Alishev -> Spring Mvc -> "12. JDBC API. Базы данных."
        Alishev -> Spring Mvc -> "13. SQL инъекции. PreparedStatement. JDBC API."
        Alishev -> Spring Mvc -> "14. ??? "

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

         - VIDEO12 - проект сделан в новой ветке "video12"
             - добавлена зависимость "mysql-connector-java"
             - подключена БД через JDBC API

         - VIDEO13
             - обновлён класс "PersonDAO"
                 - изменены методы (замена на SQL-запросы для работы с БД)

         - VIDEO14
             - добавлена зависимость "spring-jdbc"
             - обновлён класс "SpringConfig"
                 - добавлен метод "public DataSource dataSource()"
                 - добавлен метод "public JdbcTemplate jdbcTemplate()"
             - обновлён класс "PersonDAO"
             - добавлен класс "PersonMapper" -> затем заменили его на "new BeanPropertyRowMapper<>(Person.class)"