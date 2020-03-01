Use the Official PyJNIus instead
================================

[pyjnius](https://github.com/kivy/pyjnius) is a Python module to access Java classes as Python classes using JNI.

For a time, it appeared to be largely abandoned, and the ANT Center maintained a fork here for our users that included compatibility fixes for newer Java/Python versions. Fortunately, the official pyjnius project is active again (and distributes binaries via pip), so we don't need to do this anymore.

```bash
pip install -U pyjnius
```

