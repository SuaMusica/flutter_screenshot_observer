# screenshot_observer

## keep permision_handler in 6.1.3

Handle screenshot event.

Refer to
- https://github.com/nikit19/ScreenshotDetector
- https://github.com/flutter-moum/flutter_screenshot_callback

## getting started

First, add the `screenshot_observer` package to your pubspec dependencies

Initialize observer

```dart
ScreenshotObserver.initialize();
```

Add screenshot event listener

```dart
ScreenshotObserver.addListener(() {
   // TODO. handler
});
```

Dispose resource

```dart
ScreenshotObserver.dispose();
```

## TODO
- [ ] Test IOS device
