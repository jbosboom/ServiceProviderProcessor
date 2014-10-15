ServiceProviderProcessor
========================

Usage
-----

```
@ServiceProvider(SomeInterface.class)
public class MyProvider implements SomeInterface {
```

License
-------

The annotation processor itself is GPLv3+, but as the processor only
runs at compile time and no parts of the processor are embedded in
the generated files, you can use the processor with programs under
other licenses.  (If you distribute the annotation processor itself,
you need to comply with the GPL as usual.)
