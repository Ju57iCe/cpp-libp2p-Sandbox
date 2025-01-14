## [1.1.0] - 2019-01-07
- **Additions**
    - Support for Clang-5.0/6.0/7.0
    - Support for GCC-7/8
    - Support for MSVC-2017 Preview
    >
    - **Core**
        - [Is Creatable](http://boost-experimental.github.io/di/examples/index.html#is-creatable)
        - [Binding To Constructor](http://boost-experimental.github.io/di/examples/index.html#binding-to-constructor)
    >
    - **Examples**
        - [Polymorphism](http://boost-experimental.github.io/di/examples/index.html#polymorphism)
        - [Inheritance](http://boost-experimental.github.io/di/examples/index.html#inheritance)
        - [Type Erasure](http://boost-experimental.github.io/di/examples/index.html#type-erasure)
        - [Variant](http://boost-experimental.github.io/di/examples/index.html#variant)
        - [Templates](http://boost-experimental.github.io/di/examples/index.html#templates)
        - [Concepts](http://boost-experimental.github.io/di/examples/index.html#concepts)
    >
    - **Extensions**
        - [Runtime Provider](http://boost-experimental.github.io/di/extensions/index.html#runtime-provider)
        - [Injector](http://boost-experimental.github.io/di/extensions/index.html#extensible-injector)
        - [Runtime Provider](http://boost-experimental.github.io/di/extensions/index.html#extensible-injector)
>
- **Bug Fixes**
    - [Issues](https://github.com/boost-experimental/di/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aclosed+closed%3A2018-01-05..2019-01-07+)
>
- **Contributions**
    - [Kanstantsin Chernik](https://github.com/kanstantsin-chernik)
    - [Jaak Ristioja](https://github.com/jaakristioja)
    - [Gregor Jasny](https://github.com/gjasny)

## [1.0.2] - 2018-01-04
- **Additions**
    - Support for Clang-4.0
    - Support for GCC-7
    - Support for MSVC-2017
    - Fixed support for MSVC-2015 Update 3
    >
    - **Core**
        - [Support for injecting templates/concepts](http://boost-experimental.github.io/di/examples/index.html#binding-templates)
    >
    - **Extensions**
        - [Extensions are now available using header files](https://github.com/boost-experimental/di/tree/cpp14/extension/include/boost/di/extension)
        - [Extensible Injector](http://boost-experimental.github.io/di/extensions/index.html#extensible-injector)
        - [Shared Factory](http://boost-experimental.github.io/di/extensions/index.html#shared-factory)
>
- **Bug Fixes**
    - [Implementation class cannot be marked as `final`](https://github.com/boost-experimental/di/issues/249)
    - [Creation with Factory doesn't allow to pass exceptions through](https://github.com/boost-experimental/di/issues/239)
    - [Bound policy doesn't work with multiple bindings](https://github.com/boost-experimental/di/issues/238)
    - [Problems compiling with _GLIBCXX_DEBUG defined](https://github.com/boost-experimental/di/issues/235)
    - [Exception in ctor not propagated](https://github.com/boost-experimental/di/issues/227)
    - [Unable to compile with VS 2017 RC, VS 2015 works fine](https://github.com/boost-experimental/di/issues/226)
    - [Broken under VS2015 Update 3](https://github.com/boost-experimental/di/issues/219)
>
- **Contributions**
    - [Kanstantsin Chernik](https://github.com/kanstantsin-chernik)

## [1.0.1] - 2016-05-04
- **Breaking Changes**
    - [Simplified interface for policies](http://boost-experimental.github.io/di/user_guide/index.html#policies)
>
- **Additions**
    - Support for Clang-3.9
    - Support for GCC-6
    >
    - **Extensions**
        - [Contextual Bindings](http://boost-experimental.github.io/di/extensions/index.html#contextual-bindings)
        - [Serialize](http://boost-experimental.github.io/di/extensions/index.html#serialize)
>
- **Bug Fixes**
    - [Link error if di.hpp is included in two cpp-files](https://github.com/boost-experimental/di/issues/212)
    - [Creation of empty injector crashes on MSVC 2015, Update 1, x64, Debug](https://github.com/boost-experimental/di/issues/211)

## [1.0.0] - 2016-02-22
- Support for MSVC-2015+
- Support for GCC-5+
- Support for CMake 2.8+
- Support for libc++, libstdc++
- Support for Mac OS

## [0.5.0] - 2015-01-12
- C++14 version
- Support for Clang3.4+

## [0.1.0] - 2014-08-15
- C++03/C++11 version
- Support for Clang3.2+

---

[1.1.0]: https://github.com/boost-experimental/di/compare/v1.0.2...v1.1.0
[1.0.2]: https://github.com/boost-experimental/di/compare/v1.0.1...v1.0.2
[1.0.1]: https://github.com/boost-experimental/di/compare/v1.0.0...v1.0.1
[1.0.0]: https://github.com/boost-experimental/di/compare/v0.5.0...v1.0.0
[0.5.0]: https://github.com/boost-experimental/di/compare/v0.1.0...v0.5.0
[0.1.0]: https://github.com/boost-experimental/di/tree/v0.1.0
