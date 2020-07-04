# Отчёт о тестировании приложения KeyValidator

## Краткое описание

04.07.2020 - 04.07.2020 было проведено тестировании документации — инструкции по установке OpenJDK11 и руководства использования KeyValidator, тестирование установки  и тестирирование совместимости приложения KeyValidator.
На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA/issues/1
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA/issues/2
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA/issues/3
* https://github.com/Yuditskiy-o/1.1.Java-JDK-JRE-JVM-IntelliJ-IDEA/issues/4

В процессе тестирования использовались следующие артефакты:
* https://docs.google.com/spreadsheets/d/1I8G1za7qDR37qwwxzLdr1xyuCu6EB_S34ZWpFuFQcq4/edit#gid=1181522986 — Чек-лист валидации ключей KeyValidator

## Описание процесса тестирования

В качестве тестовых данных использовались данные из репозитория [javaqa-homeworks/intro](https://github.com/netology-code/javaqa-homeworks/tree/master/intro):
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md — Инструкция позволяет корректно установить Java для Window/MacOS/Linux, проблем не возникает (фактически — шаг №7 для Windows заполнен некорректно см. прикрепленный ...issues/1);
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md — Вывод приложения работает согласно документации (фактически — вывод приложения работает некорректно, см. прикрепленный ...issues/2);
* https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8 — Валидные ключи — валидны, невалидные — невалидны (фактически — были найдены дефекты, см. ...issues/3 и ...issues/4).

Тестирование производилось в следующем окружении:
* **Устройство**: PC (Windows 7 Профессиональная SP1, x64)
* **Java**: openjdk version "11.0.7" 2020-04-14
* **Браузер**: Chrome (83.0.4103.116)

