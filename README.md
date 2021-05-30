# qt5.9-base-mavericks
Make QT 5.9 work on Mavericks

QT 5.9 modified to work on OS X 10.9. Used to build a Mavericks-compatible version of the Dolphin emulator. Note that some functions were commented out and won't work.

Overall changes were minimal. `src/widgets/styles/qmacstyle_mac.mm` contains a large number of diffs because it's based on the version from QT 5.8. This was done for aesthetics and isn't strictly necessary for software to work.
