1. We will build our first widget and name it **MyApp**, which is also our main widget and is called **root widget.**

> **Widget**: In flutter, everything that appears on the screen is called **widget** such as the button, text, etc...

> **MaterialApp Widget**: This is the root widget that we need to use in every app we create.

```dart
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(

    );
  }
}
```

> **Good practice**: When you create a new class (_we will understand the class concept in the future lessons_), you should use the **PascalCase** convention to name it, which means capitalizing the first letter of each word (including the first word) and using no separators. In our case, we will create a new class widget called **HomeScreen**.

<!-- In the paragraph above, you said pascal case and in the picture below is camel case 😁 -->

![screenshot](https://lh6.googleusercontent.com/QkpfTNnKHJe-Mb09wzA9EELlV3dJXrElwS1Yotq0vnZoId4yQxt6rhg5RBPOzBciksEzoA1cD5HlFUXv8GA_p3rKGdD4lu8H7ePvv-7hTxFxLr8IleChl0_aJL6igdFKm79HEgjv)

![screenshot](https://lh5.googleusercontent.com/COTeTqOJCvhQIR1StCMTQvZB5Ea8lh9PSE4BUeS-7HdTyOqJanczbnRs83JCbljF_zCshID1BYsBswqQyJkERFvvzfvjlpClOA2fcSphLtxixP-9Bbz9qUadWUl9l7naFjoWMWvA)

> **Hint**: to create a widget fast, we can use the code snippet by typing st, then the IDE of VS Code will give us auto-completion and two snippets, one for Stateless widgets, and the other for Stateful widgets. We will choose the first one, `stateless` widget.
