6. We will see a white empty screen with the DEBUG red tag.

![screenshot](https://lh3.googleusercontent.com/4wywgJSDO4Yj6aEwpOcQtm_OD1Y1MSbzURQhJ4llG0fyYJxWsXNML3J-GxIj1ZgDtuCqewtmpMZjbYUZBl14KdSLV1cWGSNeUJ4DvVdqfZLcP-Y3B2EnacE8UHlumaYLNYq4SfR8)

7. To remove this red tag, we will use **debugShowCheckedModeBanner** named argument that inside the **MaterialApp** widget, and we will pass **false** inside it.

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
