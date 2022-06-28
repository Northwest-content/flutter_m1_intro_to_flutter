10. To keep our **Text** widget centered, we use the **Center** widget, which is a layout widget that helps us to center the widget that we pass to the **child** named argument.

    ```dart
    class HomeScreen extends StatelessWidget {
      @override
      Widget build(BuildContext context) {
        return Scaffold(
          body: Center(
            child: Text('Hello World ^_^'),
          ),
        );
      }
    }
    ```

Now, our **Text** widget is in the center of the home screen.

![screenshot](https://lh6.googleusercontent.com/5COK5Fohnffrja6KfROwIHtUZm6BG5UmUHiZViwt_-zIWbZ7DqyjZAbk1lKWWl-MqUjnLPtS1GuBi118B9ZJO7bFJG68oIFUQw6_l_GhpYGdy1xGWawKn5VVNj8DYDGXZf1d9vSV)
