# leverxCoursesJavaHW
## Первое HW: создание .jar файла с помощью консоли 
### инструкция создания:
- 1. создать каталог 
- 2. создать в этом каталоге структуру каталогов. у меня:  JarTest/com/leverxCourses/jar
- 3. создать в блокноте файл Нello.java. код в файле следующий:
```java
package com.leverxCourse.jar;
 
public class Hello{

 public static void main(String[] arg) {
        System.out.println("Hello, world !!!");
    }
}
```
- 4. далее в командной строке компилировать файл Hello.java командой javac com/leverxCourse/jar/Hello.java
- 5. создать jar файл командой jar cf hw.jar javac com/leverxCourse/jar/Hello.class
- также разобралась с установкой переменных среды JAVA_HOME и Path (правда, пока доперло почему не работает команда в консоли jar cf полгода прошло..)
