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

Functional Safety Standards are a set of international standards designed to ensure the safety of systems that have critical functions. Here is a brief introduction to the standards you mentioned:

* ISO 26262 is an automotive functional safety standard that covers the entire lifecycle of automotive systems, from concept to production. It provides guidelines for managing safety risks and ensuring that automotive systems are safe and reliable. This standard is particularly important in the development of advanced driver assistance systems (ADAS) and autonomous driving technologies.

* DO-178C is an aerospace functional safety standard that applies to the design, development, and certification of software for airborne systems. It covers the entire lifecycle of software development, from requirements analysis to maintenance. This standard ensures that the software is reliable and safe for use in aircraft, which is critical given the high stakes in aviation safety.

* IEC 62304 is a medical device functional safety standard. It applies to the entire lifecycle of medical device software, including development, validation, and maintenance. This standard aims to ensure that medical devices are safe and reliable, reducing the risk of harm to patients.

* IEC 61508 is an industrial automation and control systems functional safety standard. It applies to the entire lifecycle of safety-related systems in industrial automation and control. This standard ensures that systems are designed, developed, and maintained in a way that minimizes the risk of failure, which is crucial in industries where safety is paramount.

* EN 50128 is a railway traffic systems functional safety standard. It covers the entire lifecycle of railway systems, from design to maintenance. This standard ensures that railway systems are safe and reliable, reducing the risk of accidents and ensuring the smooth operation of the railway network.

These standards are designed to ensure that safety-critical systems are developed and maintained in a way that minimizes the risk of failure, thereby enhancing overall safety. They cover various aspects such as risk analysis, design, validation, verification, and fault management.

### Static Analysis Security Testing

Static Analysis Security Testing (SAST) is a type of software testing that analyzes the source code of a program to detect potential security vulnerabilities. Unlike dynamic testing, which involves running the application to find bugs, SAST tools scan the code itself to identify weaknesses. This can be an efficient way to find issues before the software is deployed, reducing the risk of security breaches.

* SEI CERT (Software Engineering Institute's Center for Secure Software Development): The Software Engineering Institute's Center for Secure Software Development (SEI CERT) is a research and development organization focused on enhancing the security of software systems. They offer a range of resources and services, including training, tools, and methodologies to help organizations improve the security of their software.

* CWE (Common Weakness Enumeration): The Common Weakness Enumeration (CWE) is a list of common software weaknesses. It serves as a standard for identifying, describing, and classifying software weaknesses. This helps developers understand the types of vulnerabilities they might encounter and provides a common language for discussing and mitigating these issues.

* OWASP (Open Web Application Security Project): The Open Web Application Security Project (OWASP) is a nonprofit organization that focuses on improving the security of software. They provide a wide range of free, open-source resources, including the OWASP Top 10 list of web application security risks, which helps developers prioritize their security efforts.

* DISA-ASD-STIG (Department of Defense Information Assurance Certification and Accreditation Process - Assessment Security Technical Implementation Guide): The Department of Defense Information Assurance Certification and Accreditation Process (DIACAP) - Assessment Security Technical Implementation Guide (STIG) is a set of guidelines developed by the Department of Defense (DoD) to help organizations secure their systems and applications. STIGs provide detailed instructions for configuring and securing systems to meet the DoD's security requirements.

* UL 2900 (Underwriters Laboratories Security and Privacy Framework for Internet of Things): UL 2900 is a framework developed by Underwriters Laboratories (UL) for securing the Internet of Things (IoT) devices. It provides guidelines and standards for assessing and mitigating security risks in IoT devices, focusing on areas such as device authentication, encryption, and secure software development practices.

### Security Coding Compliance Standards

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

## Safe C++
* [safecpp](https://safecpp.org/draft.html) A superset of C++ with a safe subset. 
