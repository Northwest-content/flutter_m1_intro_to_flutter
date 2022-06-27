11. We will change the style of our text to a beautiful one ^\_^. To change the text style, we use the **style** named argument inside the **Text** widget. This named argument takes **TextStyle** object.

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

As you can see in the code above, we have used different named arguments inside the **TextStyle()** object. We changed the text font size to 30, font-weight to bold style, and the color of the text to blue.

12. Finally, we have built our first app ^ \_ ^

![screenshot](https://lh5.googleusercontent.com/T-ad6-E0KUwvPl4HClTqw-K2Njv2zFIJJr5mJ6kjTPoYiVTw2-wxuO5SvwGswx4wg0jAHu_afi0wTGW6FqA8VgNxokpJ_-_eCSQNHho8ZWVTN_axGsQP2IAywGgyJtMTOqA-h_KP)
