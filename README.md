# cpp_unit_verification

* UnitTest
  - Comprehensive testing framework and tools for C/C++ code verification
* Static Code Analysis
  - Tools and standards for analyzing code quality and security

## UnitTest

### c/c++ test specification documents

#### Automotive SPICE

* [Basic Introduce to Automotive (zh_cn)](./doc/FAQ/automotive.md)
  - Chinese introduction to Automotive SPICE concepts and practices
* [Automotive_SPICE_PAM_31_EN](./doc/Automotive/Automotive_SPICE_PAM_31_EN.pdf)
  - Official Automotive SPICE Process Assessment Model 3.1 in English
* [AutomotiveSPICE_PAM_31_Chinese](./doc/Automotive/AutomotiveSPICE_PAM_31_Chinese.pdf)
  - Chinese translation of Automotive SPICE PAM 3.1

### c/c++ unittest framework and tools

* [Google Test](https://github.com/google/googletest)
  - Google's C++ test framework with rich assertion macros and test organization features
* [Google Mock](https://google.github.io/googletest/gmock_cheat_sheet.html)
  - Google's C++ mocking framework for creating mock objects
  * but gmock can not mock non-virtual method without source code modify
  * and gmock can not mock free functions without source code modify
    * one can use [C-Mock](https://github.com/hjagodzinski/C-Mock) to mock free functions
      - A C mocking framework for free functions
    * also considers [mockc](https://github.com/MickaelBlet/mockc)
      - Another C mocking framework alternative

### Code Coverage tools

* [gcov](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html)
  - GCC's native code coverage tool for analyzing program execution
    - Source code available in GCC repository: https://gcc.gnu.org/git/gcc.git under gcc/gcov/
      - [gcc-15/gcov.cc](https://gcc.gnu.org/git/?p=gcc.git;a=blob_plain;f=gcc/gcov.cc;hb=refs/heads/releases/gcc-15)
* [gcovr](https://github.com/gcovr/gcovr)
  - Python-based tool for generating code coverage reports from gcov data
* [lcov](https://github.com/linux-test-project/lcov)
  - Graphical front-end for GCC's coverage testing tool
* [grcov](https://github.com/mozilla/grcov)
  - Mozilla's code coverage tool supporting multiple languages and formats

## Static Code Analysis

### Functional Safety Standards

Functional Safety Standards are a set of international standards designed to ensure the safety of systems that have critical functions. Here is a brief introduction to the standards you mentioned:

* ISO 26262 (https://www.iso.org/standard/68383.html)
  - Automotive functional safety standard covering the entire lifecycle of automotive systems
* DO-178C (https://www.rtca.org/products/do-178c-software-considerations-in-airborne-systems-and-equipment-certification/)
  - Aerospace software safety standard for airborne systems certification
* IEC 62304 (https://www.iso.org/standard/38421.html)
  - Medical device software safety standard for healthcare applications
* IEC 61508 (https://www.iec.ch/homepage)
  - Industrial automation and control systems safety standard
* EN 50128 (https://standards.globalspec.com/std/14375471/EN%2050128)
  - Railway traffic systems safety standard for rail operations

These standards are designed to ensure that safety-critical systems are developed and maintained in a way that minimizes the risk of failure, thereby enhancing overall safety. They cover various aspects such as risk analysis, design, validation, verification, and fault management.

### Static Analysis Security Testing

Static Analysis Security Testing (SAST) is a type of software testing that analyzes the source code of a program to detect potential security vulnerabilities. Unlike dynamic testing, which involves running the application to find bugs, SAST tools scan the code itself to identify weaknesses. This can be an efficient way to find issues before the software is deployed, reducing the risk of security breaches.

* SEI CERT (https://wiki.sei.cmu.edu/confluence/display/seccode/SEI+CERT+Coding+Standards)
  - Research organization providing security training, tools, and methodologies
* CWE (https://cwe.mitre.org/)
  - Standardized list of common software weaknesses and vulnerabilities
* OWASP (https://owasp.org/)
  - Nonprofit organization providing security resources and best practices
* DISA-ASD-STIG (https://public.cyber.mil/stigs/)
  - DoD guidelines for securing systems and applications
* UL 2900 (https://www.ul.com/services/cybersecurity-assurance-program)
  - Framework for securing IoT devices and applications

### Security Coding Compliance Standards

#### MISRA C

* [MISRA/MISRA C 1998 in Russian.pdf](./doc//MISRA/MISRA%20C%201998%20in%20Russian.pdf)
  - Russian translation of the original MISRA C guidelines
* [MISRA/MISRA C 2004.pdf](./doc/MISRA/MISRA%20C%202004.pdf)
  - Updated MISRA C guidelines from 2004
* [MISRA/MISRA C 2012 Guidelines for the use of.pdf](./doc/MISRA/MISRA%20C%202012%20Guidelines%20for%20the%20use%20of.pdf)
  - Latest MISRA C guidelines from 2012

#### MISRA C++

* [MISRA/MISRA C++ 2008.pdf](./doc/MISRA/MISRA%20C++%202008.pdf)
  - Original MISRA C++ guidelines
* [MISRA/MISRA-C2012 Standards Model Summary for C  C++.pdf](./doc/MISRA/MISRA-C2012%20Standards%20Model%20Summary%20for%20C%20%20C++.pdf)
  - Summary of MISRA standards for both C and C++

#### MISRA Compliance

* [MISRA/MISRA Compliance 2016.pdf](./doc/MISRA/MISRA%20Compliance%202016.pdf)
  - Guidelines for achieving MISRA compliance
* [MISRA/MISRA Compliance 2020.pdf](./doc/MISRA/MISRA%20Compliance%202020.pdf)
  - Updated compliance guidelines for 2020

#### MISRA Checker

* [GCC-MISRAC-Checker](https://github.com/CCU-HPCLAB/GCC-MISRAC-Checker)
  - GCC-based tool for checking MISRA C compliance

#### Autosar C++

* [Autosar cpp guidelines](https://github.com/sbmueller/autosar_cpp_guidelines)
  - C++ coding guidelines for AUTOSAR automotive software

### c/c++ Warning as Error

* [GCC Warnings Options](https://gcc.gnu.org/onlinedocs/gcc/Warning-Options.html)
  - Comprehensive guide to GCC warning options and error handling

### c/c++ Cyclomatic Complexity Analyzer

* [lizard](https://github.com/terryyin/lizard)
  - Tool for analyzing code complexity metrics

## Safe C++
* [safecpp](https://safecpp.org/draft.html)
  - A superset of C++ with a safe subset for secure programming
