1. To change the text style, we use the **style** named argument inside the **Text widget**. This named argument takes the **TextStyle** object.

   ```dart
   Text(
           'Times :)',
           style: TextStyle(     // <- here
             ),
           ),

   ```

2. The **TextStyle** object has a lot of properties that you can play with to change the style of the **Text widget** such as the **color**, **font-weight** of the text, etc.

3. For example, we can increase the font size of our Text.

   ```dart
   Text(
        'Times :)',
        style: TextStyle(
          fontSize: 30,       // <- here
        ),
      ),

   ```

   ![screenshot](https://lh3.googleusercontent.com/TNDK__hl5bqpRwmkY_uEFMz7O4Hi5q2WguMj5Q1vcQ8tU3t33JwDm_R71XNz4ZQDCuJzC32hra5P4mu6BK7L1MdibMA2tV06CBw4lBQxLnUH0B8PiUHuz4L1Z9A8-tCw_ySiYIiu)
