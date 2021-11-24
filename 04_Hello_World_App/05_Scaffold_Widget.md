


4. Then we will create our Home Screen widget, and this widget will take the **Scaffold** widget.

> **Scaffold Widget**: when you want to create a new screen in Flutter, we use the **Scaffold** widget. So, each time we want to build a new screen, we will use this widget.



```dart
class HomeScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      
    );
  }
}
```



5. We will edit the **MyApp** widget, and we will use the body named argument inside the **MaterialApp** widget.



> Each widget will have named arguments, such as **body**, **child**, **appBar**, etc..; Each **named argument** has a specific job. For example, in our case, we use **home:** named arguments that inside **MaterialApp**. This named argument will help us to show the home screen, so here we pass **HomeScreen** widget that we created before.



```dart
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: HomeScreen(),
    );
  }
}
```

