# NFC-and-QRcode-app
an app to read and write into NFC chips and Create and scan QRcodes

A streamlined solution for storing, organizing, and tracking package information with integrated QR code and NFC technologies. The app allows users to create package profiles, generate QR codes, and read/write data to NFC chips, improving warehouse efficiency and package traceability.

Key Features:
User Dashboard:

A home screen that shows recent packages, delivery statuses, and quick access buttons for adding new packages.
Filters for quick search by package ID, priority, date, or other custom labels.
Package Profiles:

Form to enter package details like recipient name, product name, product ID, address, PIN, quantity, district, and state.
Fields for custom attributes if more detailed information is needed.
Photo attachment for package or any relevant images.
QR Code Generation:

Automatic QR code generation for each package profile.
Option to save the QR code as an image, which can be printed or shared.
Display of the QR code directly within the app so it can be scanned from the screen.
NFC Tag Writing:

Write package data to an NFC tag with a simple “Write to NFC” button.
Ability to encode data into a lightweight JSON format before writing to minimize space.
Notification after successful writing or error handling for unsupported tags.
NFC Tag Reading:

When an NFC tag is scanned, retrieve and display all package details.
Option to update the package details if any information has changed.
Tracking and Status Updates:

Ability to mark packages as “In Transit,” “Delivered,” “Pending,” etc.
QR code or NFC tag scanning to update the status in real-time.
Admin Settings (for Warehouses):

Multi-user access and permission settings.
Logs to monitor when and who accessed the package information.
Technical Stack and Tools:
Flutter for App Development:

Use Flutter widgets for cross-platform support on iOS and Android.
Leverage Flutter packages for QR code generation, NFC communication, and data storage.
Packages for Functionality:

QR Code Generation: qr_flutter for creating and displaying QR codes.
NFC Communication: flutter_nfc_kit for NFC read and write operations.
Database: Use sqflite for local database storage of package information.


prototype
tools used:
flutter,python,Firebase Firestore data base
 
1.CRUD functions(create,read,update,delete)
2.scan QRcodes
3.generate QRcodes
4.read NFC
5.Write NFC
