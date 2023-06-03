# Sandbox

### Android Stuff :
- jadx name.apk -> java
- apktool d name.apk, b name -o beh (https://ibotpeaches.github.io/Apktool/documentation/) -> smalli
- apk-mitm name.apk -> sign
- MobSF -> dynamic 
- httptoolkit -> intercept
- apkleaks -f name.apk -> link indentifier [ok]
- apkid name.apk  -> Obfuscators
- apkstat name.apk -> initial [ok]
- mara-framework -s name.apk [ok]
- androwarn -i name.apk --verbse 3 -r -w
- frida-tools

| No. | Tool                   | Description                                                                                               | Category                   | Code                                     | Video |
|-----|------------------------|-----------------------------------------------------------------------------------------------------------|----------------------------|------------------------------------------|-------|
| 1   | jadx                   | Decompiles an APK file to Java source code.                                                                | Reverse Engineering        | `jadx name.apk`                          | -     |
| 2   | apktool                | Disassembles and rebuilds APK files, allowing you to view and modify the resources and source code.        | Reverse Engineering        | `apktool d name.apk`, `apktool b name -o beh` | -     |
| 3   | apk-mitm               | Performs Man-in-the-Middle (MitM) attacks on APK files, allowing you to intercept and modify network traffic. | Security Testing           | `apk-mitm name.apk`                      | -     |
| 4   | MobSF                  | Provides static and dynamic analysis of APK files, including vulnerability assessment and malware detection. | Security Testing           | -                                        | -     |
| 5   | httptoolkit            | Allows interception and analysis of HTTP(S) traffic between an Android app and a server.                   | Security Testing           | -                                        | -     |
| 6   | apkleaks               | Identifies hardcoded sensitive information (e.g., API keys, passwords) within an APK file.                 | Security Analysis          | `apkleaks -f name.apk`                   | -     |
| 7   | apkid                  | Detects obfuscation techniques and obfuscators used in an APK file.                                        | Security Analysis          | `apkid name.apk`                         | -     |
| 8   | apkstat                | Provides information about an APK file, such as package name, version, permissions, and activities.        | Analysis & Information     | `apkstat name.apk`                       | -     |
| 9   | mara-framework         | Offers static and dynamic analysis capabilities for Android apps.                                          | Security Testing           | `mara-framework -s name.apk`             | -     |
| 10  | androwarn              | Static code analyzer for Android applications, identifying potential security vulnerabilities and privacy issues. | Security Analysis          | `androwarn -i name.apk --verbose 3 -r -w` | -     |
| 11  | frida-tools            | Dynamic instrumentation toolkit for Android apps, enabling you to inject and modify code at runtime.        | Dynamic Analysis           | -                                        | -     |
| 12  | ADB                    | Command-line tool for interacting with Android devices or emulators.                                       | Development & Debugging    | -                                        | -     |
| 13  | Dex2Jar                | Converts Android Dalvik Executable (DEX) files to Java Archive (JAR) format.                              | Reverse Engineering        | -                                        | -     |
| 14  | Bytecode Viewer        | Java-based tool to view and analyze the bytecode of APK files.                                             | Reverse Engineering        | -                                        | -     |
| 15  | DroidBox               | Dynamic analysis tool for Android apps, monitoring app behavior and extracting runtime information.         | Dynamic Analysis           | -                                        | -     |
| 16  | Drozer                 | Comprehensive security testing framework for Android.                                                     | Security Testing           | -                                        | -     |
| 17  | QARK                   | Scans APK files for potential security vulnerabilities and insecure coding practices.                     | Security Analysis          | -                                        | -     |
| 18  | JADX-GUI               | Graphical user interface (GUI) for JADX, making it easier to browse and analyze decompiled Java source code. | Reverse Engineering        | -                                        | -     |
| 19  | Android Studio         | Integrated Development Environment (IDE) for Android app development.                                      | Development                | -                                        | -     |
| 20  | Burp Suite             | Web application security testing tool that can be used for testing the security of Android apps.            | Security Testing           | -                                        | -     |
| 21  | Mobile-Sandbox         | Provides a cloud-based environment for analyzing Android malware samples.                                 | Malware Analysis            | -                                        | -     |
| 22  | CuckooDroid            | Extension of the Cuckoo Sandbox malware analysis system, designed specifically for Android apps.           | Malware Analysis            | -                                        | -     |
| 23  | VirusTotal             | Online service that analyzes APK files and detects potential malware using multiple antivirus engines.      | Malware Analysis            | -                                        | -     |
| 24  | DroidLysis             | Python-based framework for static and dynamic analysis of Android malware.                                | Malware Analysis            | -                                        | -     |
| 25  | Mobile Malware Analysis Toolkit (MMA-Toolkit) | Collection of scripts and tools for analyzing Android malware.                                     | Malware Analysis            | -                                        | -     |
| 26  | Androguard             | Powerful Python library for analyzing and reverse-engineering Android apps and malware.                   | Reverse Engineering        | -                                        | -     |
| 27  | DroidStatX             | Analyzes network traffic generated by Android apps and detects potential malicious behavior.               | Security Analysis          | -                                        | -     |
| 28  | Inspeckage             | Dynamic analysis tool that intercepts and logs various activities performed by an Android app.            | Dynamic Analysis           | -                                        | -     |
| 29  | AndroTotal             | Online service that analyzes APK files for potential malware and provides a detailed report.               | Malware Analysis            | -                                        | -     |
| 30  | Viper Framework        | Framework for analyzing malware samples, including Android APK files.                                     | Malware Analysis            | -                                        | -     |

