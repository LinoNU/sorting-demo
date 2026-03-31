# Sorting Algorithm Demo

An interactive, self-contained demo for CS 5001 / CS 5003 — Intensive Foundations of Computer Science at Northeastern University, Vancouver Campus.

## What it does

Students can visualize four sorting algorithms step by step and compare their actual operation counts against the theoretical worst-case complexity after sorting completes.

**Algorithms included**

- Selection sort
- Insertion sort
- Bubble sort
- Merge sort

**Controls**

- **Play / Pause** — runs the animation at the selected speed
- **Step** — advances one operation at a time
- **Shuffle** — generates a new random array
- **Array size** — adjusts n from 6 to 40
- **Speed** — five levels from slow (great for classroom walkthroughs) to fast

**After sorting completes**, a complexity chart appears showing:
- Theoretical worst-case comparisons and swaps (dashed lines) across array sizes up to n
- Actual comparisons and swaps from the run just completed (solid dots)
- Three insight cards explaining the gap between actual and worst-case performance

## Live demo

[https://linonu.github.io/sorting-demo](https://linonu.github.io/sorting-demo)

## Usage in Canvas

Embed the live demo in any Canvas page using the HTML editor (`< >` button):

```html
<iframe src="https://linonu.github.io/sorting-demo" width="100%" height="980" style="border:none;"></iframe>
```

## Technical notes

- Single self-contained HTML file — no external libraries or CDN dependencies
- Complexity chart drawn with the browser's built-in Canvas 2D API
- Works in any modern browser; tested in Chrome and Firefox
- Designed to run inside a sandboxed iframe (Canvas-compatible)

## Course context

This demo accompanies the Module 10 in-class activities on searching and sorting. Students run the Human Sort activity first (physically sorting cards in two groups of three), then use this demo to connect their empirical operation counts to the theoretical Big-O bounds.

Relevant lessons: 10.5 Simple Search, 10.6 Binary Search, 10.7 Sorting, 10.8 Sorting Using Recursion.

## Author

Dr. Lino Coria — Northeastern University, Vancouver Campus  
Spring 2026
