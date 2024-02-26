# UISpec4J

UISpec4J is an Open Source functional and/or unit testing library for Swing-based Java applications.

If you are writing a Swing application, you will appreciate UISpec4J above all for its simplicity: UISpec4J's APIs are 
designed to hide as much as possible the complexity of Swing, resulting in easy to write and easy to read test scripts. 
This is especially true when comparing UISpec4J tests with those produced using Swing or low-level, event-based 
testing libraries.

This project was "forked" from the [UISpec4J project](https://github.com/UISpec4J/UISpec4J).

## Java 17 support

The main branch now includes support for Java 17. All current tests are passing and are used by multiple projects.

## How to use

```
repositories {
    maven { url 'https://jitpack.io' }
}
dependencies {
    testImplementation 'com.github.gastendonk.uispec4j:uispec4j:2.5-g3'
}
```
