# Java Setup for Fiji/ImageJ

Fiji/ImageJ requires a specific version of Java to function correctly. This guide provides information on the Java requirements and where to obtain the necessary files.

## Java Requirements

Fiji/ImageJ typically requires Java 8. We recommend using the Temurin distribution (formerly AdoptOpenJDK) for compatibility and performance.

## Recommended Java Downloads

For optimal performance and compatibility with Fiji/ImageJ, we recommend downloading both the JRE (Java Runtime Environment) and JDK (Java Development Kit) from Adoptium.

### JRE (Java Runtime Environment)
- **Version**: 8
- **OS**: Windows
- **Architecture**: x64
- **Download Link**: [Temurin JRE 8](https://adoptium.net/temurin/releases/?version=8&os=windows&arch=x64&package=jre)

### JDK (Java Development Kit)
- **Version**: 8
- **OS**: Windows
- **Architecture**: x64
- **Download Link**: [Temurin JDK 8](https://adoptium.net/temurin/releases/?version=8&os=windows&arch=x64&package=jdk)

## Installation Notes

1. Download both the JRE and JDK from the links provided above.
2. Install both in appropriate directories. Recommended locations:
   - JRE: `C:\Program Files\Java\jre8`
   - JDK: `C:\Program Files\Java\jdk8`
3. Set the JAVA_HOME environment variable to point to your JDK installation directory.
4. Add the JDK's `bin` directory to your system's PATH.

## Important Note

These downloads are provided for convenience and are not intended to be a mirror. Always ensure you're using the most up-to-date version compatible with your Fiji/ImageJ installation.

## Verification

After installation, you can verify your Java setup by opening a command prompt and running:
```
java -version
javac -version
```

Both commands should return version information for Java 8.

Remember to restart your system or at least your development environment after making these changes to ensure all applications recognize the new Java installation.
