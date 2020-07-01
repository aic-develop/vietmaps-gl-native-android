The Vietmaps Maps SDK for Android is a library based on [Vietmaps GL Native](https://github.com/vietmaps/vietmaps-gl-native/) for embedding interactive map views with scalable, customizable vector maps onto Android devices.

## Getting Started

This particular README is for people who are interested in working on and improving the Maps SDK for Android. If you're looking for more general information and instructions on the Maps SDK:

#### Getting the source

Clone the git repository and pull in submodules:

```bash
git clone https://github.com/aic-develop/vietmaps-gl-native-android.git && cd vietmaps-gl-native-android
git submodule update --init --recursive
```

#### Installing dependencies

These dependencies are required for all operating systems and all platform targets.

- Latest stable [Android Studio](https://developer.android.com/studio/index.html)
- Update the Vietmaps Maps SDK for Android with the latest
  - Android SDK Build-Tools
  - Android Platform-Tools
  - Android SDK Tools
  - CMake
  - NDK
  - LLDB
- Modern C++ compiler that supports `-std=c++14`\*
  - clang++ 3.5 or later or
  - g++-4.9 or later
- [Node.js](https://nodejs.org/)
  - make sure [npm](https://www.npmjs.com) is installed as well
- [ccache](https://ccache.samba.org/) (optional)

**Note**: We partially support C++14 because GCC 4.9 does not fully implement the
final draft of the C++14 standard. More information in [DEVELOPING.md](../../DEVELOPING.md).

**Note**: On macOS you can install clang with installing the [Apple command line developer tools](https://developer.apple.com/download/).

### Opening the project

#### macOS

Execute the following command in this repository's root folder to generate the required build files and open the project with Android Studio:

```
make aproj
```

#### linux

run `make android-configuration` in the root folder of the project and open in Android Studio.

If you are using Arch Linux, install [ncurses5-compat-libs](https://aur.archlinux.org/packages/ncurses5-compat-libs).
