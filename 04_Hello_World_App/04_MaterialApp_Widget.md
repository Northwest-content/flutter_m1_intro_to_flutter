3. We will start building our first widget called **MyApp**, this is our main widget and it's called **root widget**.

> **Widget**: In flutter, everything that appears on the screen is called **widget** such as the button, text, etc...

> **MaterialApp Widget**: this is the root widget; we need to use this widget in every app we create.

    ```dart
    class MyApp extends StatelessWidget {
      @override
      Widget build(BuildContext context) {
        return MaterialApp(

        );
      }
    }
    ```

> **Good practice**: when you create a new class; _we will understand the class concept in the future lessons_. In our case, we create a new class widget called **HomeScreen**, when we name it we will use the **PascalCase** convention: we should capitalize the first letter of each word (including the first word), and use no separators.

![screenshot](https://lh6.googleusercontent.com/QkpfTNnKHJe-Mb09wzA9EELlV3dJXrElwS1Yotq0vnZoId4yQxt6rhg5RBPOzBciksEzoA1cD5HlFUXv8GA_p3rKGdD4lu8H7ePvv-7hTxFxLr8IleChl0_aJL6igdFKm79HEgjv)

![screenshot](https://lh5.googleusercontent.com/COTeTqOJCvhQIR1StCMTQvZB5Ea8lh9PSE4BUeS-7HdTyOqJanczbnRs83JCbljF_zCshID1BYsBswqQyJkERFvvzfvjlpClOA2fcSphLtxixP-9Bbz9qUadWUl9l7naFjoWMWvA)

> **Hint**: to create a widget fast, we can use the code snippet, by typing **st**, then the IDE (visual studio code) will give us auto-completion, and it will give us two snippets, we will choose the second one **Flutter stateless widget**. After that we will type the name of our widget. in our case we will write **MyApp**.
