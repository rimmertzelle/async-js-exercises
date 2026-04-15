# Advanced JavaScript — Async Computing

A four-lesson series on asynchronous JavaScript and server communication, designed for students with a working knowledge of basic JS (functions, arrays, objects).

Each lesson is 90 minutes and follows the teaching principles from *What the Best College Teachers Do* by Ken Bain: start from a real problem, surface misconceptions early, introduce theory as the solution, and end with reflection.

## Submitting exercises

Each exercise is submitted as a separate pull request. Create a new branch per exercise (e.g. `exercise-1-promises`) and open a PR against `main` when you are done.

Before requesting review, go through the checklist below. Reviewers will use the same list when assessing your PR, so it doubles as a self-check and a guide for what to include in your PR description.

### Pull request checklist

#### Description

- [ ] The PR title names the exercise clearly (e.g. "Exercise 2 — fetch with async/await")
- [ ] The PR description explains in one or two sentences what the exercise asked you to do
- [ ] The PR description explains how you solved it — not just *what* the code does, but *why* you made the choices you did

#### Correctness

- [ ] The code runs without errors in the browser console or Node
- [ ] The output or behaviour matches what the exercise asked for
- [ ] Edge cases are handled (e.g. what happens when the fetch fails or the response is not OK)

#### Async understanding

- [ ] It is clear why the function is marked `async` (or why a Promise is returned)
- [ ] `await` is only used inside an `async` function
- [ ] Errors from rejected Promises are caught — either with `try/catch` or `.catch()`
- [ ] No floating Promises (a Promise that is created but never awaited or `.then()`-ed)

#### Code quality

- [ ] Variable and function names describe what they hold or do
- [ ] There is no dead code (commented-out experiments, unused variables)
- [ ] The code is consistently indented and formatted

#### Reflection (written in the PR description or as a comment)

- [ ] One thing that surprised you or that you had to look up
- [ ] One question you still have, or something you would do differently next time

---

## Grading criteria

The student can show and explain the following:

1. Can students explain what an async request is and what role Promises play in a sync request.
2. How are formats (JSON/HTML) handled by the framework
3. How is an async request created in JavaScript
4. How is an async response handled in JavaScript
