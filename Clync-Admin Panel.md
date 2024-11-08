# Clync Readme




A  project created in flutter using getx. clone the project using URL mentioned below:
```
https://github.com/TechnuPur-Dev/Clync.git
```
## Getting Started

This README file offers a comprehensive overview of the project's structure, providing insights into how it adheres to specific architectural patterns, the steps needed to build and configure the project, and an outline of all dependencies used. Additionally, it includes information about the required Flutter and Dart SDK versions, ensuring that developers have the proper setup for smooth project execution.

Within this README, developers can expect to find details on the design choices guiding the architecture, such as state management techniques and dependency injection patterns, which establish a scalable and maintainable codebase. The setup and installation instructions cover essential steps, making it easy for developers to clone, configure, and run the project locally. Furthermore, the dependencies section lists all libraries and packages crucial for the project, complete with versions and roles, helping developers understand the project’s third-party requirements.

By following this README, developers can gain a solid understanding of the project's structure, architecture, and dependencies, enabling them to contribute effectively or extend the project according to their needs.

## System Requirements 

* Dart SDK: Version 3.0.0 or greater 
* Flutter SDK: Version 3.10.0 or greater 


## How to Use 

**Step 1:**

Download or clone this repo by using the link below:

```
https://github.com/TechnuPur-Dev/Clync.git
```

**Step 2:**

Go to project root and execute the following command in console to get the required dependencies: 

```
flutter pub get 
```

**Step 3:**

For IOS run the following command in your terminal: 

```
 flutter build Ios 
```

For Android run the following command in your terminal: 

```
 flutter build apk 
```

To run the app on a connected device: 

```
 flutter run 
```

## Hide Generated Files

In-order to hide generated files, navigate to `Android Studio` -> `Preferences` -> `Editor` -> `File Types` and paste the below lines under `ignore files and folders` section:

```
*.inject.summary;*.inject.dart;*.g.dart;
```

In Visual Studio Code, navigate to `Preferences` -> `Settings` and search for `Files:Exclude`. Add the following patterns:
```
**/*.inject.summary
**/*.inject.dart
**/*.g.dart
```

## Features:

* Splash
* Login
* Home
* Routing
* Theme
* Dio
* Database
* Getx (State Management)
* Encryption
* Validation
* User Notifications
* Dependency Injection
* Localization

### Libraries & Tools Used
Following tools and libraries are used in this project 

* Get 

Version: ^4.6.6 

Description: A powerful state management solution that simplifies dependency management and UI updates. 

Link: https://pub.dev/packages/get 
* connectivity_plus 

Version: ^6.0.5 

Description: Provides tools to check network connectivity status. 

Link: https://pub.dev/packages/connectivity_plus 
* Shared_preferences 

Version: ^2.3.2 

Description: Simple storage for persistent data like user preferences. 

Link: https://pub.dev/packages/shared_preferences 
* cached_network_image 

Version: ^3.4.1 

Description: Caches images for offline use to improve loading times. 

Link: https://pub.dev/packages/cached_network_image 
* Flutter_svg 

Version: ^2.0.10+1 

Description: Renders SVG images in Flutter applications. 

Link: https://pub.dev/packages/flutter_svg 
* intl 

Version: ^0.18.1 

Description: Supports internationalization and localization for dates, numbers, and messages. 

Link: https://pub.dev/packages/intl 
* blur 

Version: 3.1.0 

Description: Applies blur effects to widgets for visual appeal. 

Link: https://pub.dev/packages/blur 
* permission_handler 

Version: ^11.3.0 

Description: Manages permissions for accessing device features. 

Link: https://pub.dev/packages/permission_handler 
* flutter_screenutil 

Version: ^5.9.0 

Description: Assists with responsive layouts across different screen sizes. 

Link: https://pub.dev/packages/flutter_screenutil 
* simple_animation_progress_bar 

Version: ^1.6.0 

Description: A progress bar with simple animations. 

Link: https://pub.dev/packages/simple_animation_progress_bar 
* overlay_loading_progress 

Version: ^1.0.1 

Description: Displays loading overlays during network requests. 

Link: https://pub.dev/packages/overlay_loading_progress 
* qr_code_scanner 

Version: ^1.0.1 

Description: Enables QR code scanning functionality. 

Link: https://pub.dev/packages/qr_code_scanner 
* local_auth 

Version: ^2.2.0 

Description: Provides local authentication features like fingerprint recognition. 

Link: https://pub.dev/packages/local_auth 
* flutter_date_pickers 

Version: ^0.4.2 

Description: A customizable date picker widget. 

Link: https://pub.dev/packages/flutter_date_pickers 
* table_calendar 

Version: ^3.0.9 

Description: A highly customizable calendar widget. 

Link: https://pub.dev/packages/table_calendar 
* dio 

Version: ^5.4.1 

Description: A powerful HTTP client for network requests. 

Link: https://pub.dev/packages/dio 
* image_picker 

Version: ^1.1.2 

Description: Allows users to select images from the gallery or camera. 

Link: https://pub.dev/packages/image_picker
* flutter_secure_storage 

Version: ^9.2.2 

Description: Securely stores sensitive data. 

Link: https://pub.dev/packages/flutter_secure_storage 
* Firebase Packages 

   Version: 
  * firebase_crashlytics: ^4.1.3 

  * firebase_analytics: ^11.3.2 

  * firebase_core: ^3.5.0 

  * Firebase_messaging: ^15.1.2 

Description: Suite of libraries for integrating Firebase services. 
* google_maps_flutter 

Version: ^2.9.0 

Description: Displays Google Maps within the app. 
* flutter_local_notifications 

Version: ^17.2.3 

Description: Manages local notifications. 

Link: https://pub.dev/packages/flutter_local_notifications 
* lottie 

Version: ^3.1.2 

Description: Supports Lottie animations for rich user interfaces. 

Link: https://pub.dev/packages/lottie 
* hive 

Version: ^2.2.3 

Description: Lightweight and fast NoSQL database for structured data. 

Link: https://pub.dev/packages/hive 
* flutter_slidable 

Version: ^3.1.0 

Description: Enables sliding actions for list items. 

Link: https://pub.dev/packages/flutter_slidable 



### Folder Structure
Here is the core folder structure which flutter provides.

```
flutter-app/
|- android
|- build
|- ios
|- lib
|- test
```

Here is the folder structure we have been using in this project

```
├── android                             - It contains files required to run the application on an Android platform.
├── assets                              - It contains all images and fonts of your application.
 └── Fonts                              - Contains the font used in the application. 
 └── Gifs                               - Contains the Gifs used in the application. 
 └── Icons                              - Contains the Icons used in the application. 
 └── Images                             - Contains the Images used in the application. 
 └── Svgs                               - Contains the Svgs used in the application. 
├── ios                                 - It contains files required to run the application on an iOS platform.
├── lib                                 - Most important folder in the application, used to write most of the Dart code..
  └── main.dart                         - Starting point of the application
     ├── core                           - Core utilities and configurations. 
         └── constants                  - Stores application-wide constants. 
         └── errors                     - Error handling classes. 
         └── network                    - Network-related classes and configurations. 
         └── Localization               - Contains the translated Arabic text. 
         └── routes                     - Navigation routes for the app. 
         └── Services                   - Contains all services used in the app. 
         └── Utils                      - Contains utility classes used in the app. 
         └── Webview                    - Contains the WebView for the app.
     ├── app_export.dart                - Common imports used across the app.  
├── data                                - Data layer of the app.
      └── apiClient                     - API client classes and methods. 
      └── models                        - Data models for requests/responses. 
      └── Local_database                - Storage database used in the app. 
      └── Services                      - Socket service classes. 
├── presentation                        - It contains widgets of the screens with their controllers and the models of the whole application.
       └── bindings                     - Dependency injection bindings. 
       └── controllers                  - Contains GetX controllers (Business Logic). 
       └── models                       - UI-related models (Data Models, if needed). 
       ├── screens                      - UI layer, containing all screen widgets
             └── Authentication         - Screens related to user authentication. 
             └── Financial              - All financial-related screens of the app. 
             └── Home                   - Home screen of the app. 
             └── Onboarding             - Onboarding screen of the app. 
             └── Profile                - User profile screen of the app. 
             └── Services               - Screens related to services in the app. 
             └── Settings               - Settings screen of the app. 
             └── Social                 - Screens related to social activities in the app. 
├── theme                               - It contains app theme and decoration classes
├── widgets                             - It contains all custom widget classes
```

Now, lets dive into the lib folder which has the main code for the application.

```
1- constants - All the application level constants are defined in this directory with-in their respective files. This directory contains the constants for `theme`, `dimentions`, `api endpoints`, `preferences` and `strings`.
2- data - Contains the data layer of your project, includes directories for local, network and shared pref/cache.
3: bindings - Contains the dependency injection bindings for the application. Each screen has its own binding class where dependencies specific to that screen are defined.
4: controller - Contains the controllers that manage the state and business logic of your application's components. Each screen has its own controller class where the logic specific to that screen is defined.
5: models - Contains all the data models used in the application. Each model is located in a separate folder, making it easy to manage files related to that particular model.
6- presentation — Contains all the ui of your project, contains sub directory for each screen and including controllers and models.
7- util — Contains the utilities/common functions of your application.
8- widgets — Contains the common widgets for your applications. For example, Button, TextField etc.
9- routes.dart — This file contains all the routes for your application.
10- main.dart - This is the starting point of the application. All the application level configurations are defined in this file i.e, theme, routes, title, orientation etc.
```

### Constants

This directory contains all the application level constants. A separate file is created for each type as shown in example below:

```
constants/
|- constants.dart
|- image_constant.dart
|- api_endpoint_constant.dart
|- Color_constant.dart
```

### Data

All the business logic for API calls and loacal database (for chats) will go into this directory.
```
lib\data\api_client

lib\data\local_database

lib\data\models
```
### Bindings

Bindings are used to manage the dependencies and lifecycle of your application's components. They help in initializing controllers, services, and other dependencies required by your screens. Each screen can have its own binding class where you can define the dependencies specific to that screen.

```
lib\presentation\bindings
        └── bottom_navigation_binding.dart - Manages bottom navigation dependencies.
        └── change_number_bindings.dart - Handles dependencies for changing number.
        └── edit_profile_binding.dart - Manages profile editing dependencies.
        └── forgot_password_binding.dart - Handles dependencies for forgot password process.
        └── login_binding.dart - Manages login dependencies.
        └── qr_code_binding.dart - Handles dependencies for QR code functionalities.
        └── sign_in_binding.dart - Manages sign-in dependencies.
        └── sign_up_binding.dart - Handles dependencies for sign-up process.
        └── splash_binding.dart - Manages splash screen dependencies.
```

### Contrllers

Controllers are used to manage the state and business logic of your application's components. They help in handling user interactions, updating the UI, and communicating with services or repositories. Each screen can have its own controller class where you can define the logic specific to that screen.

```
lib\presentation\controller
        └── ServiceHub
        └── SocialHub
        └── blocked_user_controller.dart - Manages blocked user functionalities.
        └── bottom_navigation_controller.dart - Controls bottom navigation logic.
        └── change_number_controller.dart - Handles change number operations.
        └── chat_controller.dart - Manages chat functionalities.
        └── circle_detail_controller.dart - Controls circle detail view.
        └── create_circle_controller.dart - Manages circle creation process.
        └── create_pocket_controller.dart - Handles pocket creation.
        └── create_saving_pocket_controller.dart - Manages saving pocket creation.
        └── direct_chat_controller.dart - Controls direct chat functionalities.
        └── edit_poll_controller.dart - Handles poll editing.
        └── edit_profile_controller.dart - Manages profile editing.
        └── financial_controller.dart - Controls financial operations.
        └── forgot_password_controller.dart - Handles forgot password process.
        └── forward_message_controller.dart - Manages message forwarding.
        └── home_controller.dart - Controls home screen logic.
        └── login_controller.dart - Handles login operations.
        └── manage_saving_pocket_controller.dart - Manages saving pocket functionalities.
        └── notification_setting_controller.dart - Controls notification settings.
        └── poll_controller.dart - Manages poll functionalities.
        └── privacy_controller.dart - Handles privacy settings.
        └── qr_code_controller.dart - Manages QR code functionalities.
        └── scan_id_card_controller.dart - Handles ID card scanning.
        └── send_money_controller.dart - Manages money sending operations.
        └── settings_controller.dart - Controls application settings.
        └── sign_in_controller.dart - Handles sign-in operations.
        └── sign_up_controller.dart - Manages sign-up process.
        └── social_controller.dart - Controls social functionalities.
        └── splash_controller.dart - Manages splash screen logic.
        └── split_bill_controller.dart - Handles bill splitting.
        └── terms_controller.dart - Manages terms and conditions.
        └── transactions_controller.dart - Controls transaction functionalities.
```
### Models

This directory contains all the models of your application. Each model is located in a separate folder making it easy to combine group of files related to that particular model. All the model specific files will be placed in their respective directories as shown in the example below:

```
lib\presentation\models
              └── all_split_bills_model.dart - Model for all split bills.
              └── avatar_model.dart - Model for user avatars.
              └── blocked_user_model.dart - Model for blocked users.
              └── booths_model.dart - Model for booths.
              └── card_details_model.dart - Model for card details.
              └── chat_user_model.dart - Model for chat users.
              └── circle_chat_model.dart - Model for circle chats.
              └── circle_qr_scan_model.dart - Model for circle QR scans.
              └── circle_users_model.dart - Model for circle users.
              └── cirlce_Detail_model.dart - Model for circle details.
              └── error_response_model.dart - Model for error responses.
              └── financial_home_model.dart - Model for financial home.
              └── get_all_circle_model.dart - Model for getting all circles.
              └── get_all_circles_as_admin.dart - Model for getting all circles as admin.
              └── get_all_friends_model.dart - Model for getting all friends.
              └── get_all_icon_model.dart - Model for getting all icons.
              └── get_avatar_model.dart - Model for getting avatars.
              └── get_friend_request_model.dart - Model for getting friend requests.
              └── search_friend_model.dart - Model for searching friends.
              └── search_users_model.dart - Model for searching users.
              └── splash_model.dart - Model for splash screen.
              └── suggested_users_model.dart - Model for suggested users.
              └── third_user_model.dart - Model for third users.
              └── transaction_reasons_model.dart - Model for transaction reasons.
              └── user_model.dart - Model for users.
```


### Presentation

This directory contains all the ui of your application. Each screen is located in a separate folder making it easy to combine group of files related to that particular screen. All the screen specific widgets will be placed in `widgets` directory as shown in the example below:

```
lib\presentation\screens
             └── Authentication         - Screens related to user authentication. 
             └── Financial              - All financial-related screens of the app. 
             └── Home                   - Home screen of the app. 
             └── Onboarding             - Onboarding screen of the app. 
             └── Profile                - User profile screen of the app. 
             └── Services               - Screens related to services in the app. This is old design of Service, later removed.
             └── Settings               - Settings screen of the app. 
             └── Social                 - Screens related to social activities in the app.
```

### Utils

Contains the common file(s) and utilities used in a project. The folder structure is as follows: 

```
lib\core\utils
lib\core\utils\CustomDialogs
lib\core\utils\Toast
```

### Widgets

Contains the common widgets that are shared across multiple screens. For example, Button, TextField etc.

```
lib\widgets
```

### Routes
lib\core\routes\app_routes.dart
This file contains all the routes for your application. Some routes are Named and some are simple routing with Getx with Parameters

```dart
import 'package:flutter/material.dart';
class AppRoutes {
    static const String splashScreen = '/splash_screen';
  static const String onBoardingScreen = '/on_boarding_screen';
  static const String onSignUpScreen = '/on_sign_up_screen';
  static const String bottomNavigation = '/bottom_navigation';
  static const String onSignInScreen = '/on_sign_in_screen';
  static const String onForgotPasswordScreen = '/on_forgot_password_screen';
  static const String onPasswordChange = '/on_password_change_screen';
.............................
.............................
static List<GetPage> pages = [
    GetPage(
      name: initialRoute,
      page: () => SplashScreen(),
      bindings: [
        SplashBinding(),
      ],
    ),
    GetPage(
      name: onBoardingScreen,
      page: () => OnBoardingScreen(),
    ),
    GetPage(
      name: onSignUpScreen,
      binding: SignUpBinding(),
      page: () => SignUpScreen(),
    ),
    GetPage(
      name: bottomNavigation,
      bindings: [
        BottomNavigationBinding(),
      ],
      page: () => BottomNavigation(),
    ),
  
......
......]


}
```

### Main

This is the starting point of the application. All the application level configurations are defined in this file i.e, theme, routes, title, orientation etc.

```dart
import 'dart:convert';
.....................
..............................
..................................
Future<void> main() async {
  ```dart
  // Ensure Flutter framework is initialized
  WidgetsFlutterBinding.ensureInitialized();

  // Initialize deep links
  await UniServices.initDeepLinks();

  // Initialize Firebase with platform-specific options
  await Firebase.initializeApp(
    options: DefaultFirebaseOptions.currentPlatform,
  );

  // Initialize notification services
  NotificationServices().initialize();

  // Get device token for notifications and log it
  notificationServices.getDeviceToken().then((value) {
    Logger.log("Device Token: $value");
  });

  // Set up background message handler for Firebase Messaging
  FirebaseMessaging.onBackgroundMessage(backgroundHandler);

  // Record Flutter errors with Firebase Crashlytics
  FlutterError.onError = FirebaseCrashlytics.instance.recordFlutterFatalError;

  // Initialize Hive with Hive Flutter
  await Hive.initFlutter();

  // Check if encryption key exists in secure storage
  var containsEncryptionKey = await SecureUtils.storage.containsKey(key: 'encryptionKey');
  if (!containsEncryptionKey) {
    // Generate and save a new encryption key if it doesn't exist
    var key = Hive.generateSecureKey();
    var encodedKey = base64UrlEncode(key);
    await SecureUtils.saveKey(key: encodedKey);
    Logger.log("This is the ekey while writing: ${encodedKey.toString()}");
    var encryptionKey = base64Url.decode(await SecureUtils.getKey() ?? '');
    Logger.log("This is the ekey read after writing from storage: ${encryptionKey.toString()}");
  } else {
    // Retrieve and log the existing encryption key
    var encryptionKey = base64Url.decode(await SecureUtils.getKey() ?? '');
    Logger.log("Ennc ${encryptionKey.toString()}");
    if (encryptionKey.isEmpty) {
      // Regenerate and save a new encryption key if the existing one is empty
      await SecureUtils.storage.delete(key: 'encryptionKey');
      var key = Hive.generateSecureKey();
      var encodedKey = base64UrlEncode(key);
      await SecureUtils.saveKey(key: encodedKey);
      encryptionKey = base64Url.decode(await SecureUtils.getKey() ?? '');
    }
    Logger.log("This is the ekey read from storage: ${encryptionKey.toString()}");
  }

  // Register Hive adapters
  Hive.registerAdapter(ChatAdapter());
  Hive.registerAdapter(CirclesModelAdapter());
  Hive.registerAdapter(MessageListModelAdapter());
  Hive.registerAdapter(CircleMsgModelAdapter());

  // Initialize preferences and language settings
  await PrefUtils().init();
  await ChangeLanguage().loadLanguage();

  // Set preferred device orientation and run the app
  Future.wait([
    SystemChrome.setPreferredOrientations([
      DeviceOrientation.portraitUp,
    ]),
  ]).then((value) {
    Logger.init(kReleaseMode ? LogMode.live : LogMode.debug);
    Logger.log("Main function");
    runApp(MyApp(
      list: messageList,
    ));
  });
  ```

## My App main.dart

The application includes security checks to ensure it is not running on compromised devices, emulators, or while being debugged. These checks are implemented in the `MyApp` class within the `initPlatformState` method. If any of these conditions are detected, the application will display a security alert and prevent further use.
```dart
class MyApp extends StatefulWidget {
  final list;
  const MyApp({super.key, this.list});

  @override
  State<MyApp> createState() => _MyAppState();
}

class _MyAppState extends State<MyApp> with WidgetsBindingObserver {
  bool amICompromisedd = false;
  bool amIEmulatorr = false;
  bool amIDebuggedd = false;

  @override
  void initState() {
    super.initState();
    // Add observer to listen to app lifecycle changes
    WidgetsBinding.instance.addObserver(this);
    // Uncomment the following line to initialize platform state after the first frame is rendered
    // WidgetsBinding.instance.addPostFrameCallback((_) {
    //   initPlatformState();
    // });
  }

  @override
  void dispose() {
    // Remove observer when the widget is disposed
    WidgetsBinding.instance.removeObserver(this);
    super.dispose();
  }

  @override
  Future<void> didChangeAppLifecycleState(AppLifecycleState state) async {
    // Handle app lifecycle changes
    if (state == AppLifecycleState.resumed) {
      try {
        // Emit socket event to get undelivered messages when app is resumed
        SocketService.socket.emit('getUndeliveredMessages', {});
      } catch (e) {
        // Handle error
      }
    }
  }

  // Uncomment the following method to initialize platform state
  // Future<void> initPlatformState() async {
  //   bool amICompromised = false;
  //   bool amIEmulator = false;
  //   bool amIDebugged = false;

  //   try {
  //     // Check if the device is compromised, an emulator, or being debugged
  //     amICompromised = await Rjsniffer.amICompromised() ?? false;
  //     amIEmulator = await Rjsniffer.amIEmulator() ?? false;
  //     amIDebugged = await Rjsniffer.amIDebugged() ?? false;
  //   } on PlatformException {}
  //   Logger.log("compromised: $amICompromised");
  //   Logger.log("Emulator: $amIEmulator");
  //   Logger.log("Debugged: $amIDebugged");

  //   setState(() {
  //     amICompromisedd = amICompromised;
  //     amIEmulatorr = amIEmulator;
  //     amIDebuggedd = amIDebugged;
  //   });
  // }

  @override
  Widget build(BuildContext context) {
    return ScreenUtilInit(
      designSize: Size(393, 852),
      minTextAdapt: true,
      splitScreenMode: true,
      builder: (_, child) {
        return GetMaterialApp(
          navigatorKey: UniServices.navigatorKey,
          builder: (context, child) {
            return Overlay(
              initialEntries: [
                OverlayEntry(
                  builder: (context) {
                    // Show security alert if the device is compromised, an emulator, or being debugged
                    if (amICompromisedd || amIEmulatorr || amIDebuggedd) {
                      String message = '';

                      if (amICompromisedd) {
                        message += 'You cannot use the app on a compromised device. ';
                      }
                      if (amIEmulatorr) {
                        message += 'You cannot use the app on an emulator. ';
                      }
                      if (amIDebuggedd) {
                        message += 'You cannot use the app while it is being debugged. ';
                      }

                      return PopScope(
                        canPop: false,
                        child: AlertDialog(
                          title: Text('Security Alert'),
                          content: Text(message),
                          actions: <Widget>[
                            ElevatedButton(
                              child: Text('Exit'),
                              onPressed: () {
                                // Exit the app
                                SystemNavigator.pop();
                              },
                            ),
                          ],
                        ),
                      );
                    }
                    return child!;
                  },
                ),
              ],
            );
          },
          debugShowCheckedModeBanner: false,
          theme: ThemeData(
            primarySwatch: ColorConstant.customMaterialColor,
            visualDensity: VisualDensity.standard,
            appBarTheme: AppBarTheme(
              backgroundColor: ColorConstant.whiteFB,
              elevation: 0,
              scrolledUnderElevation: 0,
              shadowColor: Colors.transparent,
            ),
            textSelectionTheme: TextSelectionThemeData(
              selectionHandleColor: ColorConstant.brandGreen,
              cursorColor: ColorConstant.brandGreen,
              selectionColor: Colors.lightGreen,
            ),
            primaryColor: ColorConstant.brandGreen,
          ),
          translations: AppLocalization(),
          locale: Get.deviceLocale ?? Locale('en', 'US'), // Locale for English
          fallbackLocale: const Locale('en', 'US'),
          title: 'Clync',
          initialBinding: InitialBindings(),
          initialRoute: AppRoutes.initialRoute,
          getPages: AppRoutes.pages,
        );
      },
    );
  }
}
```


## Conclusion

In conclusion, this README provides a detailed guide to understanding and working with the Clync project. It covers the system requirements, setup instructions, and usage steps to get started with the project. The document also outlines the project's folder structure, explaining the purpose of each directory and file at general level, which helps in maintaining a clean and organized codebase. Additionally, it lists the libraries and tools used, along with their versions and descriptions, ensuring that developers are aware of the project's dependencies. By following this guide, developers can efficiently set up, run, and contribute to the Clync project, leveraging its robust architecture and comprehensive feature set.

We will be happy to answer any questions.


