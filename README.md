# Flutter-Study
import 'package:flutter/material.dart';

void main () =\> runApp(MyApp());

class MyApp extends StatelessWidget{

 @override

 Widget build(BuildContext context ){

 return MaterialApp(

 title:'Text widget',

 home:Scaffold(

 body:Center(

 child: Container(

 child: Text('Hello Container',

 style: TextStyle(

 fontSize: 18.0,

 ),

 ),

 alignment: Alignment.topLeft,

 width: 500,

 height: 600,

 padding: const EdgeInsets.fromLTRB(10.0,20.0, 0, 0), //内边距'

 margin: const EdgeInsets.all(10.0), //外边距

 decoration: new BoxDecoration(

 gradient: LinearGradient(

 colors: [Colors.lightBlue, Colors.purple,Colors.red]

 ), 

 border: Border.all(width: 5.0,color: Colors.black)

 ),

 ),

 ),

 )

 );

 }

}

![Snip20190214\_1.png](resources/1BD46E96B06DD805E75586A90A14D724.png)