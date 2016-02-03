jsonrpc-ws-android
=================
This repository contains an Android library for sending JSON-RPC messages over a WebSocket connection.

This project is part of [NUBOMEDIA](http://www.nubomedia.eu).

Documentation is available at: http://jsonrpc-ws-android.readthedocs.org/en/latest/

Repository structure
--------------------
This repository consists of an Android Studio library project. The project uses the following third-party libraries:
* [https://github.com/nubomedia-vtt/utilities-android](https://github.com/nubomedia-vtt/utilities-android)
* [https://github.com/TooTallNate/Java-WebSocket](https://github.com/TooTallNate/Java-WebSocket)
* [http://software.dzhuvinov.com/json-rpc-2.0-base.html](http://software.dzhuvinov.com/json-rpc-2.0-base.html)

Usage
--------
You can import this project to your own Android Studio project via Maven (jCenter or Maven Central) by adding the following line to module's `build.gradle` file:
```
compile 'fi.vtt.nubomedia:jsonrpc-ws-android:1.0.4'
```

If you want to build the project from source, you need to import the third-party libraries via Maven by adding the following lines to
the module's `build.gradle` file
```
compile 'fi.vtt.nubomedia:utilities-android:1.0.0'
compile 'org.java-websocket:Java-WebSocket:1.3.0'
compile 'com.thetransactioncompany:jsonrpc2-base:1.38'
```

Licensing
---------
This repository is licensed under a BSD license. See the `LICENSE` file for more information.

***Contribution policy***

You can contribute to this project through bug-reports, bug-fixes, new code or new documentation. For contributing to the project, drop a post to the mailing list providing information about your contribution and its value. In your contributions, you must comply with the following guidelines

•	You must specify the specific contents of your contribution either through a detailed bug description, through a pull-request or through a patch.

•	You must specify the licensing restrictions of the code you contribute.

•	For newly created code to be incorporated in the code-base, you must accept the code copyright, so that its open source nature is guaranteed.

•	You must justify appropriately the need and value of your contribution. There is no obligations in relation to accepting contributions from third parties.


Support
-------
Support is provided through the [NUBOMEDIA VTT Public Mailing List](https://groups.google.com/forum/#!forum/nubomedia-vtt).
