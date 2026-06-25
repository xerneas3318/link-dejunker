# Link De-Junker

A lightweight tool that automatically strips tracking cruft (`utm_source`, `utm_medium`,
`fbclid`, `gclid`, `igshid`, and friends) from any URL you copy or open — so every link
you share is clean, short, and free of tracking parameters.

> Built for the **★ STARDANCE ★ — Frictionless** challenge.

---

## The Problem

The internet is full of tiny, repetitive annoyances. One of the most common: **dirty URLs.**

Almost every link you copy from a browser, app, or email comes loaded with tracking
parameters — `?utm_source=newsletter&utm_campaign=spring&fbclid=IwAR3x...`. These params:

- Make links long, ugly, and hard to read.
- Leak where you got the link from to whoever you send it to.
- Add zero value to the person receiving the link.

Today, "cleaning" a link means manually selecting and deleting everything after the `?` —
a few seconds of friction, done thousands of times across millions of people.

## The Mission (Challenge Prompt)

> **Frictionless — Build something that makes life smoother.**
>
> The internet is full of repetitive tasks, awkward workflows, and tiny annoyances.
> Your mission is to remove one of them. Create a tool, extension, app, automation, bot,
> script, dashboard, or experiment that improves quality of life for yourself or others.
> Small ideas are welcome. Some of the best QoL tools save only a few seconds — but
> thousands of times.

**Link De-Junker** removes exactly one of those annoyances: copying a clean link.

## What It Does

- Watches the clipboard (or runs as a browser extension / CLI).
- Detects URLs and removes known tracking parameters.
- Leaves functional query params intact (e.g. `?q=`, `?id=`, `?page=`).
- Optionally unwraps redirect/shim URLs back to the real destination.

## Submission Requirements

Reviewers will look for:

1. A clear quality-of-life improvement
2. A working and usable project
3. Effort and thoughtful execution
4. Clear explanation of the problem being solved
5. Minimum 3 hours spent
6. 3 major QoL improvements

## Status

🚧 Early stage — scaffolding the core URL-cleaning logic first, then wiring up the
clipboard watcher.

## Contributing

This is a solo project — see local push notes. The sole contributor is `xerneas3318`.
