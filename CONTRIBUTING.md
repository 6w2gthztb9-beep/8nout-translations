# Contributing to 8nOut's translations

8nOut is used across Europe, and most of its non-English text — in the app,
on the website, and in the Help Centre — was drafted with AI help or by a
coder, not checked word for word by a native speaker. It ships imperfect on
purpose, because shipping it imperfect beats not translating it at all. This
repo is where that gets fixed, one string at a time, by people who actually
speak the language.

This repo does not hold 8nOut's app or website code. It holds CSV exports of
8nOut's translated strings, and a place for you to suggest a better version
of one.

## How to suggest a correction

The easiest way: open an **Issue** using the "Translation correction" form.
It asks for the exact text you're fixing, your suggested replacement, and
which language and part of the app it's on. You don't need to know anything
about how 8nOut is built.

If you're comfortable with git and would rather edit a CSV file directly and
open a **Pull Request**, that works too — the CSVs live in this repo's
`translation-review-export/` directory, one file per language.

**One string or a hundred, either is welcome.** You don't need to review a
whole file to contribute — flag the one sentence that made you wince and
move on, if that's all you have time for.

## What happens to your suggestion

A human reviews every suggestion before anything ships — nothing here
merges automatically. If it's accepted, your suggested text replaces the
current one in 8nOut's app, website, or Help Centre, in the next update.
There's no notification when that happens; if you'd like to know, feel free
to ask in the thread.

## The license

By submitting a suggestion here, you grant 8nOut a non-exclusive, worldwide,
royalty-free, perpetual license to use, modify, and include your suggested
text in 8nOut's app and website, with no expectation of payment. You keep
your copyright.

This is a license, not a handover — you're not giving up ownership of what
you wrote, and you're free to reuse your own suggested text anywhere else
you like.

**This repo's own content — the CSV files themselves — is not released
under an open-source license.** All rights reserved, same as the main 8nOut
app repo. You're welcome to read and use them to make a suggestion; this
isn't an invitation to fork the CSVs into a separate translation of 8nOut.

## Credit

If you'd like to be credited, say so when you submit — there's a checkbox
for it. Credited contributors are listed by GitHub handle in this repo's own
`CONTRIBUTORS.md`. That's scoped to this repo only: it doesn't put your name
in the app, on the website, or anywhere on social media. Those would each be
their own separate ask, with their own separate yes from you — this one
covers only the list in this file.

## A privacy note on how you submit

If you plan to open a Pull Request from your own computer (rather than using
GitHub's web-based file editor), please know that a commit made from a local
git clone carries whatever name and email address your own git is configured
with — which might be your real name and a personal email, not just your
GitHub handle. GitHub's own web editor doesn't have this problem: it commits
as your GitHub account, nothing more.

If you're not sure which you're using, or you'd rather not think about it:
**use the Issue Form.** It only ever sees your GitHub username, and it's the
easiest way to contribute anyway.
