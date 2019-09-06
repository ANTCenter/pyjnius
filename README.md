PyJNIus
=======

A Python module to access Java classes as Python classes using JNI.

This fork maintained by the ANT Center is provided for our users as a fallback when the [upstream version](https://github.com/kivy/pyjnius) is broken.


## Differences from Upstream

- We've [patched it to work on Java 12 and above](https://github.com/kivy/pyjnius/pull/435)
- This readme

View the [full comparison on GitHub](https://github.com/kivy/pyjnius/compare/master...ANTCenter:master).

## Installing

### Prerequisites
- A Java JDK such as [OpenJDK](https://jdk.java.net/) where...
   - If you're using a JDK earlier than version 9, the `JAVA_HOME` environment variable is set.
   - If you're using windows, both `javac` and `jvm.dll` are on your `PATH`
- git
- A C++ build environment. Windows users can download [C++ Build Tools](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16) for free from Microsoft.
- Python with development headers. Linux users can install their system's `python3-devel` (rpm-based) or `python3-dev` (deb based) package. Mac users can install a working python through [homebrew](https://brew.sh). Windows users should use [Anaconda](https://www.anaconda.com/distribution)
- pip (bundled with anaconda, `python3-pip` in many package managers)


### pip install command

```bash
pip install Cython
pip install -U 'git+https://github.com/ANTCenter/pyjnius.git'
```

## Find any bugs? Can't install?

Upstream accepts [issues](https://github.com/kivy/pyjnius/issues) and [pull requests](https://github.com/kivy/pyjnius/pulls). We keep an eye on these, and will generally try to make sure this fork is in a usable state.

