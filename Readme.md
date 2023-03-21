  Синтаксис Thymeleaf.

  1. Вынесенный текст (externalizing text)
    Вынесение текста позволяет использовать файлы настроек для ввода текста в шаблон. Это применяется для интернализации страниц (для каждого языка создается свой файл с сообщениями).
    Пример:
      <p th:text="#{home.welcome}">Welcome to our grocery store!</p>
    Файл настроек находится по пути /WEB-INF/templates/home_en.properties (для английского), /WEB-INF/templates/home_es.properties (для испанского).
    Синтаксис файла интернацианализации в примере:
      home.welcome=¡Bienvenido a nuestra tienda de comestibles!
      
  
      
