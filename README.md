# S4D401 – Intermediate ABAP Programming

This repository contains my exercises, implementations, and practical work from the SAP training course **S4D401 – Intermediate ABAP Programming**.

The course builds on ABAP programming fundamentals and introduces techniques for writing more efficient, reliable, and maintainable ABAP code.

It covers code analysis and automated testing, data types and type conversions, character processing, ABAP SQL optimization, internal table performance, authorization checks, object-oriented programming, exception handling, and code documentation.

The exercises are developed in an SAP ABAP Cloud training environment using Eclipse ADT (ABAP Development Tools).

**Status:** Work in Progress – exercises and implementations are added as I progress through the course.

## Exercises and Implementations

| Exercise | ABAP Object | Description |
|---|---|---|
| 1 – Copy and Understand a Template Class | `ZCL_3964_SOLUTION` | Copy and examine a template ABAP class to understand its structure and implementation. |
| 2 – Perform a Code Analysis Using the ABAP Test Cockpit | `Z3964_VARIANT` | Configure and use an ATC (ABAP Test Cockpit) check variant to perform extended program checks and analyze ABAP code. |
| 3 – Implement and Run an ABAP Unit Test | `ZCL_3964_SOLUTION` | Define and implement an ABAP Unit test for method `find_cargo_flight` of local class `lcl_carrier` to further analyze this issue. |

*Additional exercises and implementations will be documented as the course progresses.*

## Prerequisites and Development Environment

The following environment and SAP objects are used throughout the exercises:

- **Development environment:** SAP ABAP Cloud training system
- **IDE:** Eclipse with ABAP Development Tools (ADT)
- **Version control:** Git and GitHub
- **ABAP repository integration:** abapGit
- **Development package:** `ZS4D401_3964`
- **SAP training package:** `/LRN/S4D401_EXERCISE`
- **Demo package:** `/DMO/FLIGHT`

Some exercises depend on SAP-provided training objects and demo data. These are external dependencies and are not included in this repository.

## How to Run

1. Clone the repository or import it into your ABAP system using abapGit.
2. Open the development package `ZS4D401_3964` in Eclipse ADT.
3. Navigate to the relevant ABAP class or repository object.
4. Activate the object before executing or analyzing it.
5. Follow the corresponding SAP training exercise instructions.

For ATC exercises, use the configured check variant `Z3964_VARIANT`.

For ABAP Unit exercises, select the relevant ABAP class and execute the tests using **Run As → ABAP Unit Test** in Eclipse ADT.

## Tools and Technologies

- SAP ABAP / ABAP Cloud
- SAP S/4HANA training environment
- Eclipse IDE – ABAP Development Tools (ADT)
- ABAP Test Cockpit (ATC)
- ABAP Unit
- ABAP SQL
- Git and GitHub
- abapGit

## Repository Structure

```text
ABAP-SD401-EXERCISES
│
└── ZS4D401_3964
    │
    ├── ABAP Test Cockpit
    │   └── ATC Check Variants
    │       └── Z3964_VARIANT
    │
    └── Source Code Library
        └── Classes
            └── ZCL_3964_SOLUTION
```

*The repository structure will evolve as additional exercises and ABAP objects are implemented.*

## About This Project

This repository documents my practical learning journey through SAP's S4D401 Intermediate ABAP Programming course.

Beyond completing the training exercises, my goal is to understand the underlying ABAP concepts, experiment with different implementation approaches, and develop good programming practices that contribute to efficient, reliable, and maintainable SAP applications.

The implementations are based on SAP training materials, with additional experimentation where useful to reinforce the concepts.
