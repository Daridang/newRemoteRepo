# ***Работа с удалёнными репозиториями***

1. Создать аккаунт на Github
2. Создать локальный репозиторий
3. Создать удалённый репозиторий
4. Связать локальный репозиторий с удалённым
   
Получить изменения из удалённого репозитория и выполнить слияние с локальной версий:
```
git pull
```

```java
public class Main {
    public static void main(String[] args) {
        int number = 5;
        int result = square(number);
        System.out.println("The square of " + number + " is: " + result);
    }

    // Function to calculate the square of a given number
    public static int square(int number) {
        return number * number;
    }
}
```

Отправить локальную версию репозиторию на внешний 

```
git push
```