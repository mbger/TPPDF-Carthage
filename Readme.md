# TPPDF Carthage

A minimal Xcode project to reproduce [this issue](https://github.com/techprimate/TPPDF/issues/153)


# Build

1. You need `carthage` installed
   
   `$ brew install carthage`
2. Run the following command from the project root (where `Cartfile` resides):

   `carthage update --platform "iOS" --verbose`
3. If you want to get back to a clean state just remove the Carthage folder:

   `$ rm -fr Carthage`
