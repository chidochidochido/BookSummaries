# Strategies for Problem Solving: Analytical Briefing

This document provides a comprehensive synthesis of problem-solving strategies, definitions, and methodologies as outlined in the analysis of "Strategies for Problem Solving." It explores the intersection of classic logic puzzles and programming, providing a framework for approaching complex technical challenges.

## Executive Summary

Problem solving, specifically within the context of programming, is the act of writing an original program that performs a specific set of tasks while adhering to all stated constraints. Effective problem solving is a systematic process rather than a collection of random attempts. The core takeaways from this analysis include:

- **Constraint Fidelity:** A solution that ignores constraints—referred to as a _Kobayashi Maru_—is an avoidance of the problem, not a resolution.
- **Methodological Planning:** Planning is indispensable. Even if a plan is discarded during execution, the act of planning provides the necessary understanding of the problem's scope and requirements.
- **Problem Restatement and Reduction:** Formally restating a problem or reducing its scope to a simpler, solvable version can reveal "hidden" operations and stimulate progress.
- **The Power of Analogy:** Recognizing similarities between a current challenge and previously solved problems (analogies) is a primary driver of efficiency and skill development.
- **Psychological Management:** Frustration is an internal choice that hinders clear thinking. Maintaining a plan and taking strategic breaks are essential to remaining productive.

--------------------------------------------------------------------------------

## Defining Problem Solving for Programmers

In common conversation, "problem solving" often refers to the application of existing knowledge and tools to fix something broken (e.g., repairing a car). In programming, however, the term is defined as **writing an original program that performs a particular set of tasks and meets all stated constraints.**

### The Role of Constraints

Constraints are unbreakable rules regarding the problem or the methodology used to solve it. In programming, these often include:

- **Platform:** Whether the code runs on a PC, smartphone, or specific OS.
- **Performance:** Minimum requirements for graphics updates (e.g., 30 fps) or maximum response times for user inputs.
- **Memory Footprint:** Limits on the amount of memory the application can utilize.
- **Code Reference:** Restrictions on using (or requirements to use) specific open-source code.

### Avoiding the "Kobayashi Maru"

Named after a _Star Trek_ simulation where the only way to "win" was to cheat by changing the rules, a _Kobayashi Maru_ in programming is a solution that produces correct results but breaks one or more constraints. This occurs through:

1. **Accident:** The programmer fails to realize the solution is limited (e.g., only working for a specific data size).
2. **Deliberate Ploy:** Intentionally removing constraints to meet a deadline.
3. **Skill Gaps:** The programmer lacks the knowledge to meet all constraints and resorts to avoidance or outsourcing.

--------------------------------------------------------------------------------

## Lessons from Classic Puzzles

The analysis of classic riddles and puzzles provides foundational insights into how humans approach and solve complex problems.

### 1. The Fox, the Goose, and the Corn (Identifying Operations)

This riddle involves a farmer who must transport three items across a river one at a time, but cannot leave the fox with the goose or the goose with the corn.

- **The Difficulty:** Most people overlook the possibility of taking an item _back_ from the destination shore to the starting shore.
- **The Lesson:** If you are unaware of all possible actions (**operations**), you cannot solve the problem. Formally restating the problem in generic, parameterized terms (e.g., "Row the boat from one shore to the other") helps identify these hidden operations.

### 2. Sliding Tile Puzzles (Strategy and Division)

Solving an 8-tile or 15-tile grid requires a long chain of operations where individual moves may seem to move the solver further from the goal.

- **The "Train" Technique:** A method of moving tiles along a circuit while preserving their relative ordering.
- **The Lesson:** Problems are often divisible in ways that are not immediately obvious. By solving a 3x3 puzzle one row or column at a time, the solver reduces the remaining task to a smaller, easier puzzle (a 2x3 grid).

### 3. Sudoku (The Most Constrained Variable)

Sudoku requires filling a grid so that every digit appears once in every row, column, and 3x3 block.

- **The Lesson:** Start with the **most constrained part** of the problem. In Sudoku, this means identifying the square with the lowest number of possible values (ideally one). In programming, starting with the most restricted component ensures progress is not undone by later requirements.

### 4. The Quarrasi Lock (The Role of Analogy)

An alien lock uses complex terminology ("Kratzz" and "Quinicrys") and alarm suppressors to disguise its mechanics.

- **The Lesson:** This complex problem is mathematically identical to the "Fox, Goose, and Corn" riddle. Recognizing the analogy allows the solver to translate an existing solution to a new context, bypassing the need for original research.

--------------------------------------------------------------------------------

## General Problem-Solving Techniques

A formal set of techniques and principles can be applied to almost any programming challenge to ensure a systematic approach.

|   |   |
|---|---|
|Technique|Description|
|**Always Have a Plan**|Planning is indispensable for understanding capabilities and requirements, even if the plan changes. It allows for setting intermediate goals to prevent frustration.|
|**Restate the Problem**|Viewing the problem from different angles can reveal that the goal is not what it initially seemed. It also facilitates communication with supervisors or instructors.|
|**Divide the Problem**|Breaking a problem into phases reduces difficulty exponentially. Sorting 4 groups of 25 items is far less work than sorting one group of 100 items.|
|**Start with What You Know**|Complete the pieces of the code you already understand. Working partial solutions often spark ideas for the remaining difficult sections.|
|**Reduce the Problem**|Temporarily remove constraints to create a solvable version of the problem (e.g., solving a 3D coordinate problem in 2D first). This pinpoints where the specific difficulty lies.|
|**Look for Analogies**|Exploit similarities to previously solved problems. Avoid "bad reuse" (copying code you don't understand) in favor of internalizing solutions for future reference.|
|**Experiment**|Conduct controlled, hypothesis-based tests to see how code or libraries behave. This is distinct from "guessing," which lacks a belief in the outcome.|

--------------------------------------------------------------------------------

## Psychological Management: Avoiding Frustration

Frustration is a critical barrier to clear thinking and efficiency. The document posits that frustration is a decision rather than an unavoidable response.

- **Frustration as an Excuse:** Allowing anger to take over often provides a subconscious excuse for failing to solve a difficult problem.
- **Maintaining Progress:** If a programmer follows a plan and checks off intermediate goals, they are making progress, which builds confidence and mitigates frustration.
- **The Utility of Breaks:** When stuck, it is more productive to walk away or work on a different, smaller problem. Physical activity (e.g., walking, stretching) is recommended to clear the mind before returning to the task.

### Essential Quotes on Planning

"I have always found that plans are useless, but planning is indispensable." — **General Dwight D. Eisenhower**

"No plan survives first contact with the enemy." — **Helmuth von Moltke**