# Horion Client Android Port (Attempt)

## Disclaimer: Read Before Proceeding

**This project is a highly experimental and unofficial attempt to explore the feasibility of porting the Horion hacking client (originally for PC) to the Android (APK) platform.**

* **NO GUARANTEES:** There is absolutely no guarantee that this project will succeed, be functional, stable, or safe to use. The complexities involved in porting such software are immense.
* **USE AT YOUR OWN EXTREME RISK:** If any functional build is ever produced, using it on any game server (e.g., Minecraft Bedrock Edition) carries a HIGH RISK of being BANNED permanently. You are solely responsible for any consequences.
* **NOT AFFILIATED:** This project is NOT affiliated with the original Horion client developers, Mojang Studios, Microsoft, or any related entities.
* **LEGAL & ETHICAL USE:** This repository and its contents are for exploring software architecture, reverse engineering concepts (where legally permissible), and cross-platform development challenges. Do NOT use this for malicious purposes.
* **POTENTIAL FOR MALWARE:** Be extremely cautious when dealing with modified game clients from any source. This project, even if successful, could inadvertently introduce security vulnerabilities or be bundled with malware by third-party distributors if it ever leaves this repository.

## About This Project

This repository documents an attempt to make the Horion client, a well-known (and controversial) utility/hacking client for Minecraft: Bedrock Edition on PC, runnable as an Android APK.

The primary goals are:
* To understand the challenges involved in porting a Windows-based C++ application (assuming Horion's architecture) to Android.
* To explore potential methods for UI adaptation from a desktop interface to a mobile interface.
* To investigate how game-specific hooks and modifications translate across different operating systems and architectures.

## Current Status

In the works
* **Functionality:** To use all the horion hacking client features on a n Android App (APK)
* **Known Issues:** The CMakeLists.txt File Currently has glitches

## Challenges

## Planned Features (If Successful)

* I hope to port all features over succsesfully.
* A functional UI for Android devices.

## How to Contribute

Given the nature of this project, contributions are complex. If you have expertise in:
* Android NDK (C/C++) development
* Java/Kotlin for Android UI
* Reverse engineering ARM binaries
* Game hacking on Android
* Cross-platform development

...and understand the disclaimers, you could theoretically:
1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Commit your changes (git commit -am 'Add some feature').
4. Push to the branch (git push origin feature/your-feature).
5. Create a new Pull Request.

However, due to the sensitive nature, direct contributions might be heavily scrutinized or disallowed.

## Building (Theoretical Steps)

This section would outline the build process if one were established. It would likely involve:
* Android Studio
* Android NDK
* CMake or another build system for C++
* Specific libraries or dependencies

(Currently, there is no release, just the current code.)

## License

The code in this specific repository (i.e., the porting effort itself, not the original Horion code) is To be determined

The original Horion client likely has its own licensing terms (or lack thereof). This project does not grant any rights to the original Horion code beyond what its original distributors/authors allow.

**This project will be updated at least once a week until finished**
