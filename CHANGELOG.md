## 2.0.3
* Upgraded Intercom SDK to 5.3
* Upgraded Kotlin, Android Studio, Gradle and CocoaPods to latest version
* Upgraded minimum Flutter version to `1.0.0`
* Upgraded minimum Dart version to `2.0.0`
* Fixed iOS warning

## 2.0.2
* Added logEvent method (thanks @MrAlek)
* Fixed registerIdentifiedUser (thanks @Spikes042)

## 2.0.1
* Added argument validation to registerIdentifiedUser (thanks @Zazo032)

## 2.0.0
* Changed message channel name
* Added email to user registration

## 1.0.12
* Added setUserHash (thanks @Spikes042)

## 1.0.11
* Added unreadConversationCount and setInAppMessagesVisible
* Migrated to AndroidX (thanks @LeonidVeremchuk and @Zazo032)

## 1.0.10
* Updated author

## 1.0.9
* Added support for companies
* Added support for custom attributes

## 1.0.8
* Fixed issues with nullability in Intercom Android SDK

## 1.0.7
* Added Help Center support

## 1.0.6

* Fixed null check in ObjectiveC

## 1.0.5

* Fixed ObjectiveC warnings

## 1.0.4

* Converter Swift code to ObjectiveC

## 1.0.3

* Updated iOS project to Swift 4.2

## 1.0.2

* Fixed plugin name in all places

## 1.0.1

* Fixed ios headers

## 1.0.0

* Added user attributes (name, email, phone, userId and company)
* Renamed package to `intercom_flutter` because of the name clash with Intercom pod

## 0.0.4

* Fixed pod name in podspec

## 0.0.3

* Added example project
* Formatted code
* Added test

## 0.0.2

* Changed minimum SDK version to `2.0.0-dev.28.0`

## 0.0.1

* Implemented `initialize`, `registerIdentifiedUser`, `registerUnidentifiedUser`, `logout`, `setLauncherVisibility`, `displayMessenger` on both Android and iOS
