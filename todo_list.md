# Software Development Life Cycle To-Do List

**Course**: IT 140 - Introduction to Programming
**Activity**: {{ModNum}}-{{ActNum}}: {{ActivityTitle}}
**Project Name**: {{Project_name}}

## 0. Overview

{{TODO: Add a brief assignment-specific overview for the to-do list here.}}

## 1. Analysis Phase

Perform the following tasks to analyze the problem and understand the requirements for the program you will develop.

- [ ] 1.1. Read the [Software Requirement Specifications](../analysis/requirements.md) (SRS) to understand the program's requirements.

- [ ] 1.2. Complete the **TBD** section of your [Development Worksheet](./worksheet.md) to understand the requirements for the program you will be developing.

- [ ] 1.3. Review the Sample Input/Output (I/O) file to understand the program's expected behavior.

- [ ] 1.4. Complete the **IPO** section of your [Development Worksheet](./worksheet.md) to understand the program's inputs, processing, and outputs.



## 2. Design Phase

### 2.1 Software Design Document (SDD)

In the [`design\`](../design/) directory, perform the following tasks to design the program that meets the SRS.

- [ ] 2.1. Read the [Software Design Document](./design/design.md) (SDD)

### 2.2 Flowchart

- [ ] 2.2.0. Install support for Draw.io diagrams (`.drawio` files) in your IDE, if you have not done so already.
    - **VS Code | Open VSX**: Install the **Draw.io Integration** extension (hediet.vscode-drawio).
    - **JetBrains IDEs**: Install the **Diagrams.net Integration** plugin (de.docs_as_co.intellij.plugin.diagramsnet).

- [ ] 2.2.1. Open the [flowchart.drawio](./design/flowchart.drawio) file in your IDE.

- [ ] 2.2.2 {{Review the | Complete the |Create a}} [flowchart](./design/flowchart.drawio).

- [ ] 2.2.3. Mentally trace a couple of test cases through the flowchart to ensure it correctly represents the program logic and produces the expected outputs for the given inputs.

### 2.3 Pseudocode

- [ ] 2.4. {{Review | Complete | Create}} [pseudocode](./design/pseudocode.md).

- [ ] 2.5. Mentally trace a couple of test cases through the pseudocode to ensure it correctly represents the program logic and produces the expected outputs for the given inputs.

- [ ] 2.6. Complete the **Design** section of your [Development Worksheet](./worksheet.md) to document your design decisions and ensure you have a clear plan for implementing the program.

## 3. Construction Phase

In the [`src\program_name.py`](./src/program_name.py) file, perform the following tasks to implement the program according to the SDD, flowchart, and pseudocode.

- [ ] 3.1. Use block comments{{ and function definitions}} to outline code functionality based on the flowchart. Describe the purpose of each block of code in one full sentence.

- [ ] 3.2. Write code for one functional block based on pseudocode

- [ ] 3.3. Test and debug code using test cases for that functionality

- [ ] 3.4. Repeat steps 3.2 and 3.3 until all functionalities work as desired

- [ ] 3.5. Document your code with clear comments and meaningful variable and function names to make it easy to read and maintain.

## 4. Testing Phase

In the `tests\test_program_name.py` file, perform the following tasks to test the program to ensure it meets the requirements outlined in the SRS.

### 4.1. Alpha Testing

### 4.2. Beta Testing

- [ ] Test your program by {{submitting to the Instant Feedback Tool | running the provided test cases | pushing to the repository}} to verify that your program meets all the functional and nonfunctional requirements.

- [ ] Correct one error at a time, testing after each correction to ensure the program is working as expected

- [ ] Continue until all errors are resolved and the program is working as expected

### 4.3. Self-Checks

- [ ] Correct any issues identified by your IDE's linter and code analysis tools

- [ ] Compare your program against the [Acceptance Criteria Checklist](./tests/acceptance.md) (ACC) to verify that your program meets all nonfunctional requirements.

- [ ] Self-check program against the assignment rubric to ensure all criteria are met

### 4.4. Submit deliverables

Submit the following files as one submission to the assignment drop box in D2L Brightspace before the due date for acceptance testing (i.e., instructor grading and feedback).

- [ ] flowchart.drawio
- [ ] program_name.pseudo
- [ ] program_name.py
- [ ] document_name.md

## 5. Maintenance Phase (Optional)

In our SDLC, the Maintenance Phase is performed after your instructor has graded your program and provided feedback. This phase is an opportunity (not a requirement) to correct any issues they identified, as well as to make improvements to the program based on that feedback. The Maintenance Phase can be broken down into three types: corrective, perfective, and adaptive.

### 5.1 Corrective Maintenance

- [ ] Review instructor feedback and identify any issues or bugs in the program
- [ ] Repeat Phases 3 and 4 to correct one issue at a time to ensure each change works as expected
- [ ] Continue until all issues are resolved and the program is working as expected
- [ ] If permitted, resubmit the corrected program for instructor's feedback

### 5.2 Perfective Maintenance

- [ ] TODO

### 5.3 Adaptive Maintenance

- [ ] TODO
