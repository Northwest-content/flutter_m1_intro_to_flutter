4. Let's set up our `HomeScreen` widget, which returns the **Scaffold** widget.

> **Scaffold Widget**: when we want to create a new screen in Flutter, we use the **Scaffold** widget.

```dart
class HomeScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(

    );
  }
}
```

5. We will edit the **MyApp** widget, and will use the body named argument inside the **MaterialApp** widget.

> Each widget has named arguments, such as **body**, **child**, **appBar**, etc. Each **named argument** has a specific job. For example, we used the **home** named argument inside **MaterialApp**. This named argument helps us to show the home screen by passing to it the **HomeScreen** widget that we created before.

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
