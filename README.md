# cpp_unit_verification

* UnitTest
* Static Code Analysiz

## UnitTest

### c/c++ test specfication documents

#### Automotive SPICE

* [Basic Introduce to Automotive (zh_cn)](./doc/FAQ/automotive.md)
* [Automotive_SPICE_PAM_31_EN](./doc/Automotive/Automotive_SPICE_PAM_31_EN.pdf)
* [AutomotiveSPICE_PAM_31_Chinese](./doc/Automotive/AutomotiveSPICE_PAM_31_Chinese.pdf)

### c/c++ unittest framework and tools

* [Google Test](https://github.com/google/googletest)
* [Google Mock](https://google.github.io/googletest/gmock_cheat_sheet.html)
  * but gmock can not mock non-virtual method without source code modify
  * and gmock can not mock free functions without source code modify
    * one can use [C-Mock](https://github.com/hjagodzinski/C-Mock) to mock free functions  
    * also considers [mockc](https://github.com/MickaelBlet/mockc)

### Code Coverage tools

* [gcov](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html)
* [gcovr](https://github.com/gcovr/gcovr)
* [lcov](https://github.com/linux-test-project/lcov)
* [grcov](https://github.com/mozilla/grcov)

## Static Code Analysis

### Functional Safety Standards

* IS26262
* DO-178C
* IEC62304
* IEC61508
* EN50128

### c/c++ static code analysis specfication documents

#### MISRA C

* [MISRA/MISRA C 1998 in Russian.pdf](./doc//MISRA/MISRA%20C%201998%20in%20Russian.pdf)
* [MISRA/MISRA C 2004.pdf](./doc/MISRA/MISRA%20C%202004.pdf)
* [MISRA/MISRA C 2012 Guidelines for the use of.pdf](./doc/MISRA/MISRA%20C%202012%20Guidelines%20for%20the%20use%20of.pdf)

#### MISRA C++

* [MISRA/MISRA C++ 2008.pdf](./doc/MISRA/MISRA%20C++%202008.pdf)
* [MISRA/MISRA-C2012 Standards Model Summary for C  C++.pdf](./doc/MISRA/MISRA-C2012%20Standards%20Model%20Summary%20for%20C%20%20C++.pdf)

#### MISRA Compliance

* [MISRA/MISRA Compliance 2016.pdf](./doc/MISRA/MISRA%20Compliance%202016.pdf)
* [MISRA/MISRA Compliance 2020.pdf](./doc/MISRA/MISRA%20Compliance%202020.pdf)

#### MISRA Checker

* [GCC-MISRAC-Checker](https://github.com/CCU-HPCLAB/GCC-MISRAC-Checker)

#### Autosar C++

* [Autosar cpp guidelines](https://github.com/sbmueller/autosar_cpp_guidelines)

### c/c++ Warning as Error

* [GCC Warnings Options](https://gcc.gnu.org/onlinedocs/gcc/Warning-Options.html)

### c/c++ Cyclomatic Complexity Analyzer

* [lizard](https://github.com/terryyin/lizard)
