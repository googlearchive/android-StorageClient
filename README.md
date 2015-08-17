
Android StorageClient Sample
===================================

Using the OPEN_DOCUMENT intent, a client app can access a list of Document Providers
on the device, and choose a file from any of them.

Introduction
------------

This sample aims to help you understand the OPEN_DOCUMENT intent, which allows a client
application to access a list of Document Providers on the devices and choose a file from
any of them.

This sample first fires an intent to spin up the "file chooser" UI and select an image.
Then, given the content:// URI of the selected image, it shows it on the screen using a
DialogFragment. It also grabs metadata for the document specified by URI and logs that to
the screen.

To demonstrate this, click the "Show me" button to open up the Storage Access Framework
interface, and choose an image on your device.  It will be displayed in this app.

Pre-requisites
--------------

- Android SDK v23
- Android Build Tools v23.0.0
- Android Support Repository

Screenshots
-------------

<img src="screenshots/main.png" height="400" alt="Screenshot"/> 

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue:
https://github.com/googlesamples/android-StorageClient

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2014 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.
