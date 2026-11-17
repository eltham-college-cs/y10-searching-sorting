# Y10 Searching and Sorting · interactive workbooks

Static site for GitHub Pages. No build step.

```
index.html            landing page (links to each lesson)
lesson-1/index.html   Lesson 1 · Linear Search Code Builder (CodeBash tasks 1.1–1.3)
lesson-2/index.html   Lesson 2 · Binary Search Code Builder (CodeBash tasks 2.1–2.4)
.nojekyll
```

Live at https://eltham-college-cs.github.io/y10-searching-sorting/lesson-1/

## Lesson 1 · Linear Search Code Builder
- Students build each C# program one line per box; each line is checked with a plain-English error message. Curly brackets for blocks are added automatically in the assembled program.
- Tasks 1.2 and 1.3 unlock with a code. The code is shown when the previous program is complete (1.2: `SEARCH`, 1.3: `INDEX`).
- Optional trace table per task (checked, not required to move on).
- Teacher mode: add `#teacher` to the URL. Opens all tasks, shows the codes and a ▶ Model button that types each line live.
- Answers save in the browser (localStorage) on that device. Nothing is sent anywhere.

## Lesson 2 · Binary Search Code Builder
- 2.1 Binary Search Step by Step (in Main) and 2.2 Binary Search Function (from ERL): same line-by-line engine as Lesson 1. Every line carries a coloured tag for the part of the algorithm it belongs to (bounds, loop, midpoint, found, discard left, discard right, not found), matching the slides.
- Unlock codes: 2.2 `HALVE`, 2.3 `MIDDLE`. 2.4 opens automatically once 2.2 is complete.
- 2.3 Game: Human vs Binary is not scaffolded: brief, requirements checklist, syntax-only toolbox, test plan, extensions. Built in the Programiz online compiler.
- 2.4 Experiment (homework): copy the experiment program, paste in your own BinarySearch, record the Last item row for four list sizes; the page works out "times faster" and builds a results block to paste into CodeBash.
- Saves under localStorage key `y10-binary-builder-v1`. Teacher mode: `#teacher`.
