# day2-of-flutter-bootcamp

import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
          backgroundColor: Colors.blueGrey,
          appBar: AppBar(
            title: const Text("I am  Rich"),
            backgroundColor: Colors.blueGrey[900],
          ),
          body: const Center(
            child: Image(image: AssetImage('images/diamond.png')),
          )),
    ),
  );
}


//50 lightest form and 900 darkest color
//use ctrl+. for wrapping with widgets
//use ctrl+space for suggestions
//All assests will be first declared in pubspec.yaml
