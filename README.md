# Template for Flutter

# Create Flutter project
$ flutter create project_name

# Check Flutter
$ flutter doctor

# Developing and debug
$ flutter run -d Chrome
$ flutter run --enable-software-rendering

# Build an APK
$ flutter build apk --split-per-abi

# Add Android Platform Tool path to system path, to locate adb.exe
Add "C:\Tools\Android-NDK\platform-tools" to system path

# Chrome Disable CORS
Windows
Right click on desktop, add new shortcut
Add the target as "[PATH_TO_CHROME]\chrome.exe" --disable-web-security --disable-gpu --user-data-dir=~/chromeTemp
in ~/web/chrome.lnk

Open chrome.lik (with disable CORS), open Flutter web.