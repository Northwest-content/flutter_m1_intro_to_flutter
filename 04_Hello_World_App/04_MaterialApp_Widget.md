# MaterialApp Widget



3.  After that, we will start building our first widget called **MyApp**, this is our main widget called **root widget**.

>  **Widget**: In flutter, everything that appears on the screen is called **widget** such as the button, text, etc... So, here we use the **MaterialApp Widget**: this is the root widget; each time when we create a new flutter app project, we need to use this widget.



```dart
class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
   
    );
  }
}
```



> **Good practice**: when you create a new class; *we will understand the class in the future lessons*. In our case, we create a new class widget called **HomeScreen**, when we name it we will use the **UpperCamelCase** strategy: we should capitalize the first letter of each word (including the first word), and use no separators.

<img src="https://lh6.googleusercontent.com/QkpfTNnKHJe-Mb09wzA9EELlV3dJXrElwS1Yotq0vnZoId4yQxt6rhg5RBPOzBciksEzoA1cD5HlFUXv8GA_p3rKGdD4lu8H7ePvv-7hTxFxLr8IleChl0_aJL6igdFKm79HEgjv" alt="img" width="200" />






<img src="https://lh5.googleusercontent.com/COTeTqOJCvhQIR1StCMTQvZB5Ea8lh9PSE4BUeS-7HdTyOqJanczbnRs83JCbljF_zCshID1BYsBswqQyJkERFvvzfvjlpClOA2fcSphLtxixP-9Bbz9qUadWUl9l7naFjoWMWvA" alt="img" width="400" />



> **Hint**: to create a widget fast, we can use the code snippet, by typing **st**, then the IDE (visual studio code) will give us auto-completion, and it will give us two snippets, we will choose the second one **Flutter stateless widget**. After that we will type the name of our widget. in our case we will write **MyApp**.















































