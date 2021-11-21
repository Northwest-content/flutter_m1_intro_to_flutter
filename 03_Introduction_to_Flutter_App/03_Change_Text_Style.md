# Text widget



1. To change the text style, we will use a **style** named argument inside the **Text widget**. This named argument takes the **TextStyle** object.

```dart
Text(
         'Times :)',
         style: TextStyle(     // <- here 
         	),
        ),

```



2. This **TextStyle** object has several properties that we can use to change the style of the **Text widget**.



3. For example, we can increase the font size of our Text. When you save the change you will see the font size of the text widget will increase.

> Note: this **TextStyle** object has a lot of properties you can play with, such as the **color** of text, **font-weight** of text, etc..



```dart
Text(
              'Times :)',
              style: TextStyle(                       
                fontSize: 30,       // <- here
              ),
            ),

```



![screenshot](https://lh3.googleusercontent.com/TNDK__hl5bqpRwmkY_uEFMz7O4Hi5q2WguMj5Q1vcQ8tU3t33JwDm_R71XNz4ZQDCuJzC32hra5P4mu6BK7L1MdibMA2tV06CBw4lBQxLnUH0B8PiUHuz4L1Z9A8-tCw_ySiYIiu)







