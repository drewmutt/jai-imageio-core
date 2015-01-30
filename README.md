#  JAI Image I/O Tools

The Java Advanced Imaging API provides a set of object-oriented interfaces that support a simple, high-level programming model which lets you manipulate images easily.

This is a pure Java fork which removes the C library components, as a result the JPEG and PNG formats are not available. The supported formats are: bmp, gif, jpeg2000, pcx, pnm, raw, tiff, wmbp.

## System Requirements

- J2SE 1.4  or later.
- Apache Ant 1.6  or later

## Dependencies

The build requires that Java Advanced Imaging (JAI) either be installed
in the J2SDK used for the build or that jai_core.jar be on the CLASSPATH.

## Build

```
ant
```

This will build the Java code for the `jj2000.*`, `com.sun.media.imageio.*`, `com.sun.media.imageioimpl.*`, `com.sun.media.jai.imageioimpl` and `com.sun.media.jai.operator` packages. 

The output JAR file can be found at `build/opt/lib/ext/jai_imageio.jar`.

## License

The source for Image I/O Tools is covered by two seperate licenses:

- Classes in the `com.sun.media` package are under the 3-clause BSD
license given in `LICENSE-SUN.txt`.
- Classes in the `jj2000.j2k` package are under a bespoke license 
  given in `LICENSE-JJ2K.txt`. The license is not OSI approved, nor
  is it GPL compatible.
