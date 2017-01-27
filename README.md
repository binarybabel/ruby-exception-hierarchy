# Ruby Exception Hierarchy

**User reference of Ruby Language core exceptions in tree-format.**

[![Build Status](https://travis-ci.org/binarybabel/ruby-exception-hierarchy.svg?branch=latest)](https://travis-ci.org/binarybabel/ruby-exception-hierarchy) [![Latestver](https://lv.binarybabel.org/catalog-api/ruby/latest.svg?v=2.2.0)](https://lv.binarybabel.org/catalog/ruby/latest)

The latest branch is updated automatically when new versions of Ruby are released, through the use of webhooks provided by the [Latestver](https://lv.binarybabel.org) dependency tracking tool, a [BinaryBabel OSS Project](https://github.com/binarybabel/latestver#readme). _Check the [GitHub Tags](https://github.com/binarybabel/ruby-exception-hierarchy/releases) to review older results._

## Ruby 2.2.0 Exceptions

_**`rescue`** statements default to `StandardError` and sub-classes_

```
BasicObject
  Exception
    NoMemoryError
    ScriptError
      LoadError
      NotImplementedError
      SyntaxError
    SecurityError
    SignalException
      Interrupt
    StandardError
      ArgumentError
        UncaughtThrowError
      EncodingError
      FiberError
      IOError
        EOFError
      IndexError
        KeyError
        StopIteration
      LocalJumpError
      NameError
        NoMethodError
      RangeError
        FloatDomainError
      RegexpError
      RuntimeError
      SocketError
      SystemCallError
      ThreadError
      TypeError
      ZeroDivisionError
    SystemExit
    SystemStackError
    fatal
```

## Maintainer
* The build mechanics for this project are available at:
  * https://github.com/binarybabel/ruby-exception-hierarchy/tree/worker
* Unless otherwise noted, all source-controlled files are released under the [MIT License](https://opensource.org/licenses/MIT).


                                                                                  0101010
                                                                               0010011
                                                                             110101
                                                                           0011
                                                                                    0100010
                                                                       1010    0010101000001
                                                                      010101110100111101010010
                                                                     01     0011000100
                 Project maintained by BinaryBabel
                                                                       0100
                                                                    01001001    binarybabel.org
                                                                   0100111001    000001010001110
                                                                  101       0010010000010100100101
                                                              00111          0010011110100011001010
                                                              0110            10000010100111001000100