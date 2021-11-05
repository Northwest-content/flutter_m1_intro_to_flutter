# Text Widget



8. When we create the application interface in Flutter we make a composition of widgets by nesting them one inside the other. In our example, we will use **Text** widget which helps us to draw text inside an app. We will draw "**Hello World ^_^**" text inside the app, and we will pass the **Text** widget inside the **body** named arguments that inside the **Scaffold** widget.

```dart
class HomeScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Text('Hello World ^_^'),  // <--- Here
    );
  }
}
```



9. After that, we will see our "**Hello World**" text be on the top left of the screen.



![img](https://lh3.googleusercontent.com/iN0pClKhmp4ny_1PxRbzM7Y22jKI82Fsfg41mxj1Jd5zJBah4DLfM84FPZzHPYly-b0TwxlslGKm4Wiz2dgp7ZppBtx94ZvvndCwWM-HF_PkjU39LeLKiRGlC_zXQOwTsLkt4gZc)