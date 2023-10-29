# JavaStudy
### Section 7
#### 코딩 연습 2: Hello World 프린트
- 박시현
        
```java
public class Exercise {
    public static void main(String[] args) {
        //print "Hello World"
        System.out.println("Hello World");
                // 버퍼에 엔터까지 입력됨,개행문자

        // System.out.print("Hello World");
                // 버퍼에 엔터는 입력안됨 개행문자 X
    }
}
```
        
- 김민지

```java
public class Exercise {
    public static void main(String[] args) {
        //print "Hello World"
        System.out.println("Hello World");
    }
}
```
        
- 김다훈

```java
public class Exercise {
    public static void main(String[] args) {
        //print "Hello World"
        System.out.println("Hello World");
    }
}
```
#### 코딩 연습 3: 시간 변환기
    - 박시현
        
        ```java
        public class TimeConverter {
            public static int convertHoursToMinutes(int hours) {
                if (hours < 0)
                    return -1;
                    
                return hours * 60;
            }
            
            public static int convertDaysToMinutes(int days) {
                if (days < 0)
                    return -1;
                return days * 24 * 60;
            }
        }
        ```
        
    - 김민지
        
        ```java
        public class TimeConverter {
            public static int convertHoursToMinutes(int hours) {
                if (hours < 0)
                    return (-1);
                return hours * 60;
            }
            
            public static int convertDaysToMinutes(int days) {
                if (days < 0)
                    return (-1);
                return days * 24 * 60;
            }
        }
        ```
        
    - 김다훈
        
        ```java
        public class TimeConverter {
            public static int convertHoursToMinutes(int hours) {
                if (hours < 0)
                    return -1;
                return hours * 60;
            }
            
            public static int convertDaysToMinutes(int days) {
                if (days < 0)
                    return -1;
                return days * 24 * 60;
            }
        }
        ```




