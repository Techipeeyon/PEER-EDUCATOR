import 'package:flutter/material.dart';
 
 void main() => runApp(HelloMohajir());
 
 class HelloMohajir extends StatelessWidget {
   @override
   Widget build(BuildContext context) {
 
     //MaterialApp acts as a wrapper to the app and 
    //provides many features like title, home, theme, etc.   
    return MaterialApp(
      title: 'Hello Mr.Mohajir',

      //Scaffold acts as a binder that binds the appBar,
      //bottom nav bar and other UI components at their places     
      home: Scaffold(

        //AppBar() widget automatically creates a material app bar
        appBar: AppBar(
          title: Text('Hello Mr.Mohajir'),
        ),

        //Center widget aligns the child in center
       body: Center(
          child: Text('Hello Mr.Mohajir'),
       ),
     ),
   );
  }
}