# Flutter Json View

Displaying json models in a Flutter widget

## Getting Started

### Add dependency

   ```
   dependencies:
  flutter_json_view: ^1.0.0
   ```

### Add import package

   ```import 'package:flutter_json_view/flutter_json_view.dart';```
   
## Easy to use

Add one of the constructors in your code

### String constructor

   ```JsonView.string('{"key":"value"}'),```
   
### Asset file constructor

   ```JsonView.asset('assets/data.json'),```
   
### Map constructor

   ```JsonView.map({"key":"value"}),```
   
## Customization

🎨 The package was created in order to be able to customize your json view

   ```
   JsonView.string(
    '{"key":"value"}',
    theme: JsonViewTheme(
      keyStyle: TextStyle(
        color: Colors.black54,
        fontSize: 16,
        fontWeight: FontWeight.w600,
      ),
      doubleStyle: TextStyle(
        color: Colors.green,
        fontSize: 16,
      ),
      intStyle: TextStyle(
        color: Colors.green,
        fontSize: 16,
      ),
      stringStyle: TextStyle(
        color: Colors.green,
        fontSize: 16,
      ),
      boolStyle: TextStyle(
        color: Colors.green,
        fontSize: 16,
      ),
      closeIcon: Icon(
        Icons.close,
        color: Colors.green,
        size: 20,
      ),
      openIcon: Icon(
        Icons.add,
        color: Colors.green,
        size: 20,
      ),
      separator: Padding(
        padding: EdgeInsets.symmetric(horizontal: 8.0),
        child: Icon(
          Icons.arrow_right_alt_outlined,
          size: 20,
          color: Colors.green,
        ),
      ),
    ),
  ),
   ```