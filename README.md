Fork from sign_in_button.

A Flutter plugin for iOS and Android for generating sign-in buttons for different social media account.

> Feedback and Pull Requests are most welcome!

## Installation

Add to pubspec.yaml.

```yaml
dependencies:
  ...
  sign_in_button_plus: ^1.0.0
```

## Usage Example

import sign_in_button.dart

```dart
import 'package:sign_in_button_plus/sign_in_button_plus.dart';
```

### For built-in buttons.

```dart
SignInButton(
  Buttons.google,
  onPressed: () {},
)

// with custom text
SignInButton(
  Buttons.google,
  text: "Sign up with Google",
  onPressed: () {},
)
```

### For mini buttons.

```dart
SignInButton(
  Buttons.facebook,
  mini: true,
  onPressed: () {},
)
```

### For self-build buttons.

```dart
SignInButtonBuilder(
  text: 'Sign in with Email',
  icon: Icons.email,
  onPressed: () {},
  backgroundColor: Colors.blueGrey.shade700,
)
```

### Built-in Buttons contain

```dart
enum Buttons {
  email,
  google,
  googleDark,
  facebook,
  facebookNew,
  gitHub,
  apple,
  appleDark,
  linkedIn,
  pinterest,
  tumblr,
  twitter,
  reddit,
  quora,
  yahoo,
  hotmail,
  xbox,
  microsoft,
}
```

<img src="https://github.com/anmolthedeveloper/sign_in_button_plus/raw/master/showcase.png" width="300">

**Refer to example folder and the source code for more information.**
