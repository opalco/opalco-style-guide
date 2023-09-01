# Opalco Style Guide

This repository outlines what should and should not be done when working on Opalco's Github repositories. It isn't very long, so just take the time to read it all. It will be worth it in the long run.

## **Basic Format**

These points outline the basic format every file should follow.

- Comment on top of file stating "This file is licensed under the \_\_\_ License. View LICENSE at the root of the project for more info."
- Spaces instead of tabs
- 2 spaces instead of 4
- Before each commit, clippy is required to be ran before being pushed
- If a function call's arguments don't all fit on one line, break them apart
- Parentheses should NOT have internal padding
- LF line endings

## **Comments**

Yes, comments are **required** or else no one would know what is going on.

- Comments should tell _why_ instead of _what_ if they are inside a function
- A comment should be placed before structs, traits, and functions
- When a comment is placed before structs, traits, or functions, they must tell _what it does_
- Comments before public functions, structs, or traits should additionally say _how to use it_

## **Other Guidelines**

These guidelines are very helpful in many scenarios.

- Prioritize security over performance unless performance is very important in that unit
- Test your code before making a commit (using Rust's built-in testing library)
- Use of options is recommended when available
- Try to avoid unnecessary complexity (if there is an easier way, do it)

## **Git Commits**

There are no guidelines here (currently, at least).
