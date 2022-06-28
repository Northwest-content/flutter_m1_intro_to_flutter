When we create the application interface in Flutter, we make a composition of widgets by nesting them one inside the other.

8. In our example, we will use the **Text** widget, draw "**Hello World ^\_^**" text inside the app, and pass the **Text** widget to the **body** named arguments that's inside the **Scaffold** widget.

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

9. We will see our **Hello World** text at the top left of the screen.

![screenshot](https://lh3.googleusercontent.com/iN0pClKhmp4ny_1PxRbzM7Y22jKI82Fsfg41mxj1Jd5zJBah4DLfM84FPZzHPYly-b0TwxlslGKm4Wiz2dgp7ZppBtx94ZvvndCwWM-HF_PkjU39LeLKiRGlC_zXQOwTsLkt4gZc)
