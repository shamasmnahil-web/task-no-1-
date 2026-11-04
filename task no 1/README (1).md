# AI Lab Tasks

**Submitted by:** Mnahil Fatima  
**Submitted to:** Sir Rasikh  
**Roll Number:** SU92-BSAIM-F25-046

## Project Overview

This repository contains three AI Lab tasks covering an introduction to Artificial Intelligence, a simple reflex agent, and the difference between conversational performance and general intelligence.

## Tasks Included

### Task 1: Historical Timeline of Artificial Intelligence

A chronological overview of selected milestones in AI:

- **1950 – Alan Turing's Imitation Game:** Alan Turing proposed the imitation game in his paper *Computing Machinery and Intelligence*, an idea commonly associated with the Turing Test.
- **1956 – Dartmouth Conference:** The Dartmouth Summer Research Project helped establish Artificial Intelligence as a separate research field and popularized the term.
- **1974–1980 – First AI Winter:** AI research experienced reduced funding and interest because early systems did not meet high expectations.
- **1986 – Backpropagation and Neural Networks:** Research on backpropagation helped make the training of multilayer neural networks more effective.
- **2012 – AlexNet and GPU Computing:** AlexNet demonstrated the value of deep neural networks, large image datasets, and GPU computation for image recognition.

**Conclusion:** These milestones show the development of AI from early theoretical ideas into a modern field supported by neural networks, large datasets, and powerful computing systems.

### Task 2: Simple Reflex Agent – Room Temperature Control

A Python program demonstrating a simple reflex agent for an air-conditioning system. The agent receives a desired temperature and room sensor information, including the current temperature and whether the room is occupied.

The intended decision logic is:

- If the room is unoccupied, set the target to `off`.
- If the current temperature is higher than the desired temperature, set the target to `AC on`.
- If the current temperature equals the desired temperature, set the target to `AC off`.
- The program compares the new target with the previous mode to decide whether to send a command or report that no command is needed.

The sample room data includes `Store_room`, `Bed_room`, and `empty_room`, with temperature and occupancy values.

**Code note:** The code supplied for this task appears to contain a few implementation issues that may prevent it from running as intended. For example, `none` should be Python's `None`, the branch for a temperature below the desired temperature does not assign a `target`, and the room-processing statements appear to be outside the `for` loop in the pasted version. These are noted rather than silently changing the submitted code.

### Task 3: Why Passing a Conversational Test Does Not Prove General Intelligence

This task explains why fluent conversation alone is not sufficient evidence of general intelligence.

It covers:

- The Turing Test and its connection to Alan Turing's 1950 imitation game.
- What a conversational test observes, such as fluency, clarity, relevance, and the ability to maintain a conversation.
- What it does not establish, including reliable reasoning, factual accuracy, transfer of learning, consistent real-world performance, or consciousness.
- An example comparing `0.8` and `0.75` to show that a confident-sounding answer can still be incorrect.
- A multi-task performance benchmark as an additional way to evaluate an AI system across different tasks.

**Conclusion:** Conversational ability is useful to evaluate communication, but broader testing is needed to assess reasoning, accuracy, and performance on unfamiliar tasks.

## Files

- `README.md` – Overview of the project and its three AI Lab tasks.
- `info.txt` – Plain-text summary of the submitted work.

## References

The references listed in the submitted Task 3 document include:

1. Turing, A. M. (1950). *Computing Machinery and Intelligence*. Mind, 59(236), 433–460.
2. Starace, G., et al. (2025). *PaperBench: Evaluating AI's Ability to Replicate AI Research*. Proceedings of the 42nd International Conference on Machine Learning.

The Task 1 document also lists sources alongside individual timeline milestones. Those source names are retained in the original assignment document.
