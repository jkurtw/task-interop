# Google Play services `Task` interoperability sample app

There are many asynchronous libraries available that developers enjoy using.
`Task`s align conceptually to several popular Android approaches to managing
asynchronous code, and they can be straightforwardly converted to other
primitives, including the `ListenableFuture` and Kotlin coroutines [which are
recommended by AndroidX](https://developer.android.com/jetpack/androidx/releases/concurrent).

This app provides examples interoperability for (using open source libraries):

* Kotlin Coroutine
* Guava ListenableFuture
* RxJava Observable

For more information:
https://developers.google.com/android/guides/tasks

Getting started
---------------
Clone this project to your workstation using a git client. You can use the
[instructions from GitHub](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/cloning-a-repository)
if you need guidance.

This project uses the Gradle build system. To build this project, use the
`gradlew build` command or use "Import Project" in Android Studio.

For more resources on learning Android development, visit the
[Developer Guides](https://developer.android.com/guide/) at
[developer.android.com](https://developer.android.com).

Support
-------

Please report issues with this sample in this project's issues page:
https://github.com/googlesamples/task-interop/issues

License
-------

```
Copyright 2020 Google, Inc.

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
```
