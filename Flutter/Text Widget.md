import 'package:flutter/material.dart';

void main () =\> runApp(MyApp());

class MyApp extends StatelessWidget{

 @override

 Widget build(BuildContext context ){

 return MaterialApp(

 title:'Text widget',

 home:Scaffold(

 body:Center(

 child:Text(

 'Hello Text Widget, 明天就是情人节咯，第三方第三方的开始范德萨范德萨发生的范德萨范德萨范德萨范德萨范德萨发完非法违法第三方第三',

 textAlign: TextAlign.start,

 maxLines: 3,

 overflow: TextOverflow.ellipsis,

 style: TextStyle(

 fontSize: 20.0,

 color: Color.fromARGB(255, 255, 125, 125)

 ),

 )

 ),

 )

 );

 }

}