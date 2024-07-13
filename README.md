# complex

A library for Dart developers. It is awesome.

## Usage

A simple usage example:

    import 'package:my_complex/my_complex.dart';

    main() {
      var c = new Complex.cartesian(0,2);
      var p = new Complex.polar(2, math.PI/2);
      print(c.equals(p));
    }

## Features and bugs

Please file feature requests and bugs at the [issue tracker][tracker].

[tracker]: http://example.com/issues/replaceme

This library has been updated to work with Dart SDK version 3.4.1 (stable) and now includes null safety.