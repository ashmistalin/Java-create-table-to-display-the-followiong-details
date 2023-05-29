# Java-create-table-to-display-the-followiong-details

## AIM:
To Write a program that would print the information (name, year of joining, salary, address) of three employees by creating a class named 'Employee'.
```
 Name           Year of joining              Address
Robert                1994                           64C- WallsStreat
Sam                    2000                           68D- WallsStreat
John                    1999                            26B- WallsStreat
```

## PROGRAM:
```
public class Employees{
    public void emp1() {
        String name1 = "Robert";
        int yoj = 1994;
        String add = "64C- WallsStreat";
        System.out.println(name1 + "         " + yoj + "           " + add);
    }
    public void emp2() {
        String name2 = "Sam";
        int yoj2 = 2000;
        String add2 = "64D- WallsStreat";
        System.out.println(name2 + "            " + yoj2 + "           " + add2);
    }
    public void emp3() {
        String name3="John";
        int yoj3=1999;
        String add3="26B- WallsStreat";
        System.out.println(name3+"           "+yoj3+"           "+add3);
    }


}

Main function:

public class Main {
    public static void main(String[] args) {
        System.out.println("Name      Year of joining      Address");
        Employee e=new Employee();
        e.emp1();
        e.emp2();
        e.emp3();
    }
}
```

## OUTPUT:
```

C:\Users\Dell\.jdks\openjdk-19.0.2\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.3.3\lib\idea_rt.jar=4572:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.3.3\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath "C:\Users\Dell\IdeaProjects\java java\out\production\java java" Main
Name      Year of joining      Address
Robert         1994           64C- WallsStreat
Sam            2000           64D- WallsStreat
John           1999           26B- WallsStreat

Process finished with exit code 0
```


