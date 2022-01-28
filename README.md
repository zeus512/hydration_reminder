# Hydration Reminder Android

[![Verify and Build](https://github.com/bombinatetech/kuhu_android/actions/workflows/verification.yml/badge.svg)](https://github.com/bombinatetech/kuhu_android/actions/workflows/verification.yml)

This is the android codebase of [Hydration Reminder](playstore link need to be updated).

## What is Hydration Reminder App?

Reminds consumption of water on regular intervals 

## Getting Started

### Dependencies

* Git
* JDK 11
* Androdi Studio
* ssh (optional but recommanded)
* zsh (Optional)
* Fork (Optional)

### Setup

1. Clone the project.
```bash
git clone git@github.com:zeus512/hydration_reminder.git
cd hydration_reminder
git fetch --unshallow
git remote set-branches origin '*'
git fetch -v
```

2. Setup Environment
	* This is an optional step if you want to use terminal for build.
	* Make sure your JAVA_HOME and ANDROID_SDK_HOME is pointing to correct path.
	* Accept sdkmanager licences with `yes | $ANDROID_SDK_HOME/tools/bin/sdkmanager –licenses` 
	* Build debug version of app with `./gradlew assembleDebug`

### General FAQs

Q: What is buildSrc?
</br>
A: [Click Here](https://docs.gradle.org/current/userguide/organizing_gradle_projects.html#sec:build_sources "Click Here")

Q: What we use for CI/CD
</br>
A: We use Github Actions for CI/CD purpose.

Q: What merge stretegy i should follow?
</br>
A: We recommand git squash merge and that is the default option to merge PR's to develop aka mainline.

## License

This project is a property of DarkByte Technologies Pvt Ltd and contents of this repository should be limited to the members of same.
