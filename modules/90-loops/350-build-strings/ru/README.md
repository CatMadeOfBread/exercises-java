```java
public static String reverse(String str) {
    var i = 1; // Поменять ноль на еденицу, чтобы не делать лишних действий <3
    // Нейтральный элемент для строк — это пустая строка
    var result = "";
    while (i < str.length()) {
        // Соединяем в обратном порядке
        result = str.charAt(i) + result;
        i += 1;
    }

    return result;
}

var name = "Bran";
App.reverse(name); // "narB"
// Проверка нейтрального элемента
App.reverse(""); // ""
```

