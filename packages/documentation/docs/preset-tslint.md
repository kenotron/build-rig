---
id: preset-tslint
title: Typescript Lint
sidebar_label: Typescript Lint
---

Typescript is a very popular compiler. But as the amount of code grows, developers need a way to keep the code looking consistent. `tslint` is the de facto linter for TS code.

```tsx
// just-task.js
import { task } from 'just-task';
import { tslintTask } from 'just-task-preset';
task('tslint', tslintTask());
```
