Simple snackbar

## Usage

```import 'package:snackbar/snackbar.dart';```

```dart
// Simple snackbar
snack("Hello World");

// Snack with a button
snackUndo("Deleted XYZ", () {
  // It was NOT undone, proceed with deletion
}, undoText: "Undo",
    duration: const Duration(seconds: 5));

// Clear the current snackbar
clearSnackbar();
```
