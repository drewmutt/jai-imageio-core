#  JAI Image I/O Tools

The Java Advanced Imaging API provides a set of object-oriented interfaces that support a simple, high-level programming model which lets you manipulate images easily.

This is a pure Java fork which removes the C library components, as a result the JPEG and PNG formats are not available. The supported formats are: bmp, gif, jpeg2000, pcx, pnm, raw, tiff, wmbp.

## System Requirements

- J2SE 1.4  or later.
- Apache Ant 1.6  or later

## Build

```
ant
```

This will build the Java code for the `jj2000.*`, `com.sun.media.imageio.*`, `com.sun.media.imageioimpl.*`, `com.sun.media.jai.imageioimpl` and `com.sun.media.jai.operator` packages. 

## License

The source for Image I/O Tools is covered by two seperate licenses:

- Classes in the `com.sun.media` namespace are under the 3-clause BSD
license given in `LICENSE-SUN.txt`.

- Classes in the `jj2000.j2k` namepace are under a bespoke license 
  given in `LICENSE-JJ2K.txt. The license is not OSI approved, nor
  is it GPL compatible.
