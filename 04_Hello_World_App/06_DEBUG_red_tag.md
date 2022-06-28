When we run the app, we see a white empty screen with the DEBUG red tag.

![screenshot](https://lh3.googleusercontent.com/4wywgJSDO4Yj6aEwpOcQtm_OD1Y1MSbzURQhJ4llG0fyYJxWsXNML3J-GxIj1ZgDtuCqewtmpMZjbYUZBl14KdSLV1cWGSNeUJ4DvVdqfZLcP-Y3B2EnacE8UHlumaYLNYq4SfR8)

6. To remove the red tag, use the **debugShowCheckedModeBanner** named argument inside the **MaterialApp** widget, and set it to false.

   ```dart
   class MyApp extends StatelessWidget {
     @override
     Widget build(BuildContext context) {
       return MaterialApp(
         debugShowCheckedModeBanner: false, // <--- Here
         home: HomeScreen(),
       );
     }
   }
   ```
