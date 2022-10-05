# great_places

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


# Environment Variables
List of variables used in the app.
- GOOGLE_API_KEY

Sample using with launch.json from VSCode:
```` json
{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "great_places",
      "request": "launch",
      "type": "dart",
      "flutterMode": "debug",
      "toolArgs": [
        "--dart-define",
        "GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY"
      ],
      "deviceId": "emulator-5554"
    },
  ]
}
```
