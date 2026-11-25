# NIMS BugStrike

**Find the Bug. Fix the Code. Win the Challenge.**

## Competition Overview

NIMS BugStrike is a competitive programming **BUG FIXING competition** (BUS - Bug Fixing). Participants receive pre-written C++ programs containing intentional bugs. They must analyze, debug, and repair the provided programs, then submit the corrected programs for evaluation.

**This is not a code-writing competition.** Participants are expected to fix the existing code for each problem, not replace it with an unrelated program or solve a different task.

## Competition Format

| Detail | Description |
| --- | --- |
| Competition name | NIMS BugStrike |
| Competition type | C++ Bug Fixing Competition (BUS - Bug Fixing) |
| Tagline | Find the Bug. Fix the Code. Win the Challenge. |
| Programming language | C++17 |
| Total questions | 10 |
| Total marks | 180 |
| Duration | 90 minutes |
| Target audience | College students |

### Difficulty and Marks

| Difficulty | Questions | Marks per question | Total marks |
| --- | ---: | ---: | ---: |
| Easy | 4 | 10 | 40 |
| Medium | 4 | 20 | 80 |
| Hard | 2 | 30 | 60 |
| **Total** | **10** | - | **180** |

### Question List

| Difficulty | Question | Problem | Marks |
| --- | ---: | --- | ---: |
| Easy | 1 | Array Sum - The Missing Sum | 10 |
| Easy | 2 | Reverse the Message | 10 |
| Easy | 3 | The Highest Score | 10 |
| Easy | 4 | Even or Odd Detector | 10 |
| Medium | 5 | Find the Target - Binary Search | 20 |
| Medium | 6 | Second Largest Distinct Element | 20 |
| Medium | 7 | Balanced Brackets | 20 |
| Medium | 8 | Merge Two Sorted Arrays | 20 |
| Hard | 9 | Detect the Cycle - Linked List | 30 |
| Hard | 10 | Binary Tree Level Order Traversal | 30 |

## Competition Rules

- Submit solutions in C++17.
- Each question provides an existing C++ program with intentional bugs.
- Debug and repair the provided program. Do not replace the problem with an unrelated solution.
- Sample cases are included in each question file. Hidden test cases will also be used.
- Partial marks may be awarded based on the test cases passed.
- There is no negative marking.
- A submission that does not compile receives zero marks for that submission.
- Keep each question's required input and output format unchanged.

## Evaluation and Scoring

Submissions are compiled with a C++17-compatible compiler and evaluated for correctness against sample and hidden test cases. Scores are based on the assigned marks for each question and may be partial, depending on the test cases passed. Compilation errors receive zero marks for that submission; incorrect answers do not incur negative marks.

## Submission Guidelines

1. Open the C++ file for the question you are attempting.
2. Read its problem description, input/output format, constraints, and sample carefully.
3. Repair the existing program while keeping its intended task and required input/output format.
4. Compile and test the repaired program. Submit the corrected source file for that question as directed by the competition organizers.
5. Submit only participant work. Do not include organizer-only answer keys or solutions.

Compile and run a question file with:

```bash
g++ -std=c++17 Easy/Q1_Array_Sum.cpp -o solution
./solution
```

Replace the example path with the file you are working on. On Windows, run the generated executable with:

```powershell
.\solution.exe
```

## Repository Structure

```text
NIMS-BugStrike/
├── README.md
├── Easy/
│   ├── Q1_Array_Sum.cpp
│   ├── Q2_Reverse_String.cpp
│   ├── Q3_Maximum_Element.cpp
│   └── Q4_Even_Odd.cpp
├── Medium/
│   ├── Q5_Binary_Search.cpp
│   ├── Q6_Second_Largest.cpp
│   ├── Q7_Valid_Parentheses.cpp
│   └── Q8_Merge_Arrays.cpp
├── Hard/
│   ├── Q9_Linked_List_Cycle.cpp
│   └── Q10_Level_Order_Traversal.cpp
└── Solutions/
    └── (organizer-only answer keys; not for participants)
```

Keep all participant question files in the `Easy/`, `Medium/`, and `Hard/` folders. Organizer answer keys and corrected solutions must remain separate from participant-facing materials and must not be distributed to participants.

## Final Note

Think logically, trace the program carefully, and test your changes against different cases. Find the bug, fix the code, and enjoy the challenge!
