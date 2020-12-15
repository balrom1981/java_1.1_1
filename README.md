**Дата тестирования** - 15.12.2020

Было проведено тестирование:
1. Инструкции по установке OpenJDK11 работает под вашу ОС
1. Приложение запускается и совместимо с Java 11
1. Приложение работает согласно руководству использования

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие **дефекты**:
1. https://github.com/balrom1981/java_1.1_1/issues/1
1. https://github.com/balrom1981/java_1.1_1/issues/2
1. https://github.com/balrom1981/java_1.1_1/issues/3

**Процесс тестирования:**
1. Объект тестирования:
    * Тестирование инструкции по установке OpenJDK11 на OC Windows
    * Тестирование запуска и совместимости приложения с Java 11
    * Тестирование работы приложения  KeyValidator.class согласно инструкции
1. Методы:
    * пошаговое тестирование инструкции по установке OpenJDK11 на Windows
    * функциональное тестирование приложения при помощи введения валидных/невалидных ключей
1. Заведение баг репортов на Github
1. Анализ полученных результатов

**Тестовые данные:**
* инструкции по установке OpenJDK11 на OC Windows https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md
* Руководство для тестирования приложения https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md

**Окружение:**
* OC Windows 10 Pro
* 64-bit Operation System, x64-based processor
* Java version "11.0.9.1" 2020-11-04