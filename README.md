# leverxCoursesJavaHW
## First HW: create a .jar file using console
### instruction:
- 1. create a directory
- 2. create a directory structure in this directory. i.e: JarTest / com / leverxCourses / jar
- 3. create a java file in notepad. the code in notepad i.e:
```java
package com.leverxCourse.jar;
 
public class Hello{

 public static void main(String[] arg) {
        System.out.println("Hello, world !!!");
    }
}
```
- 4. then, using console, compile the Hello.java file with the command javac com / leverxCourse / jar / Hello.java
- 5. create jar file in console using command jar cf hw.jar javac com / leverxCourse / jar / Hello.class 
- P.S environment variables JAVA_HOME and Path must be set.
