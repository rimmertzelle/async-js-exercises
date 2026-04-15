## What does this PR do?

<!-- One or two sentences: what did the exercise ask, and how did you solve it? -->

## Reflection

<!-- One thing that surprised you or that you had to look up -->

<!-- One question you still have, or something you would do differently next time -->

---

## Checklist

#### Description

- [ ] The PR title names the exercise clearly (e.g. "Lesson 1 — Exercise 2")
- [ ] The PR description explains what the exercise asked you to do
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
