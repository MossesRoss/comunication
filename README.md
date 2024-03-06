Error: Couldn't resolve the package 'cloud_firestore' in 'package:cloud_firestore/cloud_firestore.dart'.
lib/main.dart:3:8: Error: Not found: 'package:cloud_firestore/cloud_firestore.dart'
import 'package:cloud_firestore/cloud_firestore.dart';
       ^
lib/main.dart:29:7: Error: The getter 'FirebaseFirestore' isn't defined for the class '_ChatScreenState'.
 - '_ChatScreenState' is from 'package:twototwo/main.dart' ('lib/main.dart').
Try correcting the name to the name of an existing getter, or defining a getter or field named 'FirebaseFirestore'.
      FirebaseFirestore.instance.collection('messages').add({
      ^^^^^^^^^^^^^^^^^
lib/main.dart:31:22: Error: The getter 'Timestamp' isn't defined for the class '_ChatScreenState'.
 - '_ChatScreenState' is from 'package:twototwo/main.dart' ('lib/main.dart').
Try correcting the name to the name of an existing getter, or defining a getter or field named 'Timestamp'.
        'createdAt': Timestamp.now(),
                     ^^^^^^^^^
lib/main.dart:51:48: Error: 'QuerySnapshot' isn't a type.
              builder: (context, AsyncSnapshot<QuerySnapshot> snapshot) {
                                               ^^^^^^^^^^^^^
lib/main.dart:47:23: Error: The getter 'FirebaseFirestore' isn't defined for the class '_ChatScreenState'.
 - '_ChatScreenState' is from 'package:twototwo/main.dart' ('lib/main.dart').
Try correcting the name to the name of an existing getter, or defining a getter or field named 'FirebaseFirestore'.
              stream: FirebaseFirestore.instance
                      ^^^^^^^^^^^^^^^^^
lib/main.dart:82:52: Error: The getter 'accentColor' isn't defined for the class 'ThemeData'.
 - 'ThemeData' is from 'package:flutter/src/material/theme_data.dart' ('../../flutter/packages/flutter/lib/src/material/theme_data.dart').
Try correcting the name to the name of an existing getter, or defining a getter or field named 'accentColor'.
      data: IconThemeData(color: Theme.of(context).accentColor),
                                                   ^^^^^^^^^^^
Unhandled exception:
FileSystemException(uri=org-dartlang-untranslatable-uri:package%3Acloud_firestore%2Fcloud_firestore.dart; message=StandardFileSystem only supports file:* and data:* URIs)
#0      StandardFileSystem.entityForUri (package:front_end/src/api_prototype/standard_file_system.dart:34:7)
#1      asFileUri (package:vm/kernel_front_end.dart:732:37)
#2      writeDepfile (package:vm/kernel_front_end.dart:870:21)
<asynchronous suspension>
#3      FrontendCompiler.compile (package:frontend_server/frontend_server.dart:676:9)
<asynchronous suspension>
#4      starter (package:frontend_server/starter.dart:102:12)
<asynchronous suspension>
#5      main (file:///b/s/w/ir/x/w/sdk/pkg/frontend_server/bin/frontend_server_starter.dart:13:14)
<asynchronous suspension>

Target kernel_snapshot failed: Exception


FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':app:compileFlutterBuildDebug'.
> Process 'command '/home/moss/flutter/bin/flutter'' finished with non-zero exit value 1

* Try:
> Run with --stacktrace option to get the stack trace.
> Run with --info or --debug option to get more log output.
> Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 5s
Exception: Gradle task assembleDebug failed with exit code 1
