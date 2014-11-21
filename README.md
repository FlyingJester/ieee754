
### Read/write IEEE754 floating point numbers from/to a Buffer or array-like object.

## methods

The `ieee754` object has the following functions:

```
ieee754.read = function (buffer, offset, isLE, mLen, nBytes)
ieee754.write = function (buffer, value, offset, isLE, mLen, nBytes)
```

The arguments mean the following:

- buffer = the buffer
- offset = offset into the buffer
- value = value to set (only for `write`)
- isLe = is little endian?
- mLen = mantissa length
- nBytes = number of bytes

## what is ieee754?

The IEEE Standard for Floating-Point Arithmetic (IEEE 754) is a technical standard for floating-point computation. [Read more](http://en.wikipedia.org/wiki/IEEE_floating_point).

This version of this package has been modified to work with older and non-Node.JS style JavaScript environments, such as Sphere. This version is intended to be used as a component of the TurboSphere runtime.

## mit license

Copyright (C) 2013 [Feross Aboukhadijeh](http://feross.org) & Romain Beauxis.
Copyright (C) 2014 [Martin McDonough](https://github.com/FlyingJester)
