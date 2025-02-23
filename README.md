<<<<<<< HEAD
<<<<<<< HEAD
# Firebase_Authen
=======
# firebase_authen

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
>>>>>>> 536b4b2 (Initial commit)
=======
# FirebaseAuthen
# Firebase_Authen
dart pub global activate flutterfire_cli
ติดตั้งเครื่องมือ FlutterFire CLI เพื่อใช้ในการตั้งค่าและเชื่อมต่อ Firebase กับ Flutter โปรเจค

flutterfire configure --project=<project_id>
ใช้เพื่อ เชื่อมต่อโปรเจค Flutter กับ Firebase โดยเลือกโปรเจค Firebase ที่ต้องการ

npm install -g firebase-tools
ติดตั้ง Firebase CLI สำหรับการจัดการ Firebase ผ่าน Command Line 

firebase login
ล็อกอินเข้าสู่ Firebase ผ่าน CLI เพื่อใช้งานคำสั่งต่าง ๆ

flutter pub add firebase_core firebase_auth cloud_firestore
ติดตั้ง Firebase SDK สำหรับ Flutter เพื่อเชื่อมต่อกับ Firebase (Authentication, Firestore)

firebase deploy 
ใช้สำหรับ Deploy แอป Flutter Web ไปยัง Firebase Hosting

firebase init
เริ่มต้นโปรเจค Firebase และเลือกบริการที่ต้องการใช้งาน 

npm install firebase
ใช้สำหรับการเชื่อมต่อกับ Firebase Services

Firebase.initializeApp()
ตั้งค่าการเชื่อมต่อ Firebase ในแอป Flutter

createUserWithEmailAndPassword()
สร้างบัญชีผู้ใช้ใหม่ด้วยอีเมลและรหัสผ่าน

signInWithEmailAndPassword()
เข้าสู่ระบบด้วยอีเมลและรหัสผ่าน

sendPasswordResetEmail()
ส่งอีเมลรีเซ็ตรหัสผ่านให้กับผู้ใช้

signOut()
ออกจากระบบ Firebase
>>>>>>> 78666d0aa58dca3df73afacc76feced8ecd279c3
