### Пример: поздрав по име

Да напишем програма, която въвежда името на потребителя и го поздравява с текста "**Hello, *име***".

```csharp           
var name = Console.ReadLine();
Console.WriteLine("Hello, {0}!", name);
```

В този случай, изразът **`{0}`** e заместен от **първия** подаден аргумент, който в примера е променливата **`name`**:

![](/assets/chapter-2-images/00.Greeting-by-name-01.jpg)

#### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.org/Contests/Practice/Index/504#2](https://judge.softuni.org/Contests/Practice/Index/504#2).