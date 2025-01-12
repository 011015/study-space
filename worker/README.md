# Worker Demo

This demo shows how to use `Worker` to run a long-time task in background thread, and prevent blocking main thread.

## showcase

[open home page](https://011015.github.io/study-space/worker/index.html)

## description

1. open home page.
2. click `start` button and see the animation effect.
3. animation effect ends before you switch `optimize` button and click `block` button, to observe the difference between using Worker and not using Worker including `doing` and `done` state, animation effect and `INP` metric(available in Chrome DevTools).
