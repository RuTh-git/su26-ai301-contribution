# Contribution [1]: Remove test --only case sensitivity

**Contribution Number:** 1  
**Student:** Ruth Mercy  
**Issue:** [MFlowCode/MFC#1533](https://github.com/MFlowCode/MFC/issues/1533)  
**Project Fork:** [RuTh-git/MFC](https://github.com/RuTh-git/MFC)  
**Status:** Phase I Complete

---

## Why I Chose This Issue

I picked this issue because it fixes a genuine quality-of-life annoyance in the daily developer workflow. Right now, running a specific test with `./mfc.sh test --only <label>` forces you to remember exact, non-standard capitalizations like "STL" or "slip." Making this flag case-insensitive is a straightforward usability win. It’s a great entry point for me because the fix lives inside the Python-based toolchain wrapper rather than the core Fortran simulation math, allowing me to get familiar with the repo's CLI architecture without getting bogged down in complex fluid dynamics.

Working on this matches my background in Python and scripting well, making it an ideal project to practice the full open-source workflow—from local testing to opening a clean pull request. It also gives me a chance to see how a major high-performance computing project handles its development tooling and test automation. Resolving this issue will give me a solid foundation in the codebase so I can take on more advanced tasks down the line.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
