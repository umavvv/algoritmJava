Ответ выведит все числа в данном случае 4
```
  String howOld= "4 years old";
        return howOld.replaceAll("[^0-9]","");
```
Ответ если в контейнере есть перечисленные слова выведит true при этом переделав входной тип данных в нижний регистер(greetings)
```
public static boolean validateHello(String greetings){
    return Stream.of("hello", "ciao", "salut", "hallo", "hola", "ahoj", "czesc")
                        .anyMatch(x -> greetings.toLowerCase().contains(x));
  }  
}
```
