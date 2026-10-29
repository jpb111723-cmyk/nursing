# Nursing Reviewer (ADHD-friendly)

Short sprints, one question at a time, instant feedback, no penalties.

## Add a topic (2 steps)
1. Put a new file in `questions/`, e.g. `questions/maternal.txt`
2. Add one line to `topics.json`:
   `{ "id": "maternal", "name": "Maternal & Child Health", "file": "questions/maternal.txt" }`

Any number of topics works. The home screen builds itself from `topics.json`.

## Question format
Blank line between questions. `Why:` is optional but great for learning.

```
Which site is most commonly used to check an adult's pulse?
A. Femoral
B. Popliteal
C. Radial
D. Pedal
Answer: C
Why: Easy to reach and the standard routine site.
```

## Hosting
Turn on GitHub Pages (Settings > Pages > main branch). Opening index.html by double-click will not load the question files; use Pages or `python3 -m http.server`.

Progress is saved in your browser only.
