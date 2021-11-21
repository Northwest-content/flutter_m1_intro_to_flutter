# TextStyle



11. Right now, we don't like the style of text, so we will change it to a beautiful style ^_^. To change the text style, we will use the **style** named argument inside the **Text** widget. This named argument takes **TextStyle**.

```dart
class HomeScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      body: Center(
        child: Text(
          'Hello World ^_^',
          style: TextStyle(                  // <- here
            fontSize: 30,                    
            fontWeight: FontWeight.bold, 
            color: Colors.blue,
          ),
        ),
      ),
    );
  }
}
```



As you see in the above code, we used the different named arguments inside the **TextStle()**. We changed the font size of the text to 30, font-weight to bold style, and we change the color of the text to blue color.





12. Finally, we have built our first app ^ _ ^

    ![screenshot](https://lh5.googleusercontent.com/T-ad6-E0KUwvPl4HClTqw-K2Njv2zFIJJr5mJ6kjTPoYiVTw2-wxuO5SvwGswx4wg0jAHu_afi0wTGW6FqA8VgNxokpJ_-_eCSQNHho8ZWVTN_axGsQP2IAywGgyJtMTOqA-h_KP)
