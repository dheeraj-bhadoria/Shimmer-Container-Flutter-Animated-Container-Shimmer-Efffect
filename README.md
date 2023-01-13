# Shimmer Container Flutter  - Add shimmer effect in your app using shimmer container

It will show a beautiful and customized shimmer effect in your app. You can show it when you are loading any data from API or show some loading effect. 


![image description](https://github.com/dheeraj-bhadoria/Shimmer-Container-Flutter-Animated-Container-Shimmer-Efffect/blob/main/shimmer.gif)

## Platform Support

| Android | iOS | MacOS | Web | Linux | Windows |
| :-----: | :-: | :---: | :-: | :---: | :-----: |
|   ✔️    | ✔️  |  ✔️   | ✔️  |  ✔️   |   ✔️    |


##Use this package as a library

Depend on it

Run this command:

With Dart:

```yaml

    $ dart pub add shimmer_container

```

With Flutter:

```yaml

$ flutter pub add shimmer_container

```

This will add a line like this to your package's pubspec.yaml (and run an implicit dart pub get):

```yaml

    dependencies:
    shimmer_container: ^0.0.1

```


Alternatively, your editor might support dart pub get or flutter pub get. Check the docs for your editor to learn more.
Import it

Now in your Dart code, you can use:

```dart

import 'package:flutter_shakemywidget/flutter_shakemywidget.dart';

```
# How to use

```dart

    @override
    Widget build(BuildContext context) {
      // This method is rerun every time setState is called, for instance as done
      // by the _incrementCounter method above.
      //
      // The Flutter framework has been optimized to make rerunning build methods
      // fast, so that you can just rebuild anything that needs updating rather
      // than having to individually change instances of widgets.
      return Scaffold(
          ShimmerContainer(
            height: 80,
            width: 350,
            radius: 4,
            highlightColor: Color(0xffF9F9FB),
            baseColor: Color(0xffE6E8EB),
          ));
    }
```


## Complete Example

```dart

    import 'dart:async';
    
    import 'package:flutter/material.dart';
    
    import '../lib/shimmer_container.dart';
    
    void main() {
      runApp(const MyApp());
    }
    
    class MyApp extends StatelessWidget {
    
      const MyApp({super.key});
    
      // This widget is the root of your application.
      @override
      Widget build(BuildContext context) {
        return MaterialApp(
          title: 'Shimmer Container Example',
          theme: ThemeData(
            // This is the theme of your application.
            //
            // Try running your application with "flutter run". You'll see the
            // application has a blue toolbar. Then, without quitting the app, try
            // changing the primarySwatch below to Colors.green and then invoke
            // "hot reload" (press "r" in the console where you ran "flutter run",
            // or simply save your changes to "hot reload" in a Flutter IDE).
            // Notice that the counter didn't reset back to zero; the application
            // is not restarted.
            primarySwatch: Colors.blue,
          ),
          home: const MyHomePage(title: 'Shimmer Container Example'),
        );
      }
    }
    
    class MyHomePage extends StatefulWidget {
    
      const MyHomePage({super.key, required this.title});
    
      // This widget is the home page of your application. It is stateful, meaning
      // that it has a State object (defined below) that contains fields that affect
      // how it looks.
    
      // This class is the configuration for the state. It holds the values (in this
      // case the title) provided by the parent (in this case the App widget) and
      // used by the build method of the State. Fields in a Widget subclass are
      // always marked "final".
    
      final String title;
    
      @override
      State<MyHomePage> createState() => _MyHomePageState();
    }
    
    
    class _MyHomePageState extends State<MyHomePage> {
    
      @override
      void initState() {
        // TODO: implement initState
        super.initState();
      }
    
      void safeSetState() {
        if (mounted) {
          setState(() {});
        }
      }
    
      @override
      Widget build(BuildContext context) {
        // This method is rerun every time setState is called, for instance as done
        // by the _incrementCounter method above.
        //
        // The Flutter framework has been optimized to make rerunning build methods
        // fast, so that you can just rebuild anything that needs updating rather
        // than having to individually change instances of widgets.
        return Scaffold(
          appBar: AppBar(
            // Here we take the value from the MyHomePage object that was created by
            // the App.build method, and use it to set our appbar title.
            title: Text(widget.title),
          ),
          body: Center(
            // Center is a layout widget. It takes a single child and positions it
            // in the middle of the parent.
            child: SingleChildScrollView(
              child: Column(
                children: [
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                  ShimmerContainer(
                    height: 80,
                    width: 350,
                    radius: 4,
                    highlightColor: Color(0xffF9F9FB),
                    baseColor: Color(0xffE6E8EB),
                  ),
                  SizedBox(height: 10,),
                ],
              ),
              scrollDirection: Axis.vertical,
            ),
          ),
        );
      }
    }


```


## License

MIT License

Copyright (c) 2022 Dheeraj Singh Bhadoria

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.