# resize_observer
A Flutter widget that calls a callback when its child is resized.

## Usage
1. Import the package
   ```dart
   import 'package:resize_observer/resize_observer.dart';
   ```

2. Observe resizes
   ```dart
   return ResizeObserver(
     onResized: (Size oldSize, Size newSize) { /* ... */ },
     child: /* ... */,
   );
   ```
   
## Inspiration
- [amirh/size_observer](https://github.com/amirh/size_observer)
- [`SizeChangedLayoutNotifier`](https://api.flutter.dev/flutter/widgets/SizeChangedLayoutNotifier-class.html) (`package:flutter/widgets.dart`)
