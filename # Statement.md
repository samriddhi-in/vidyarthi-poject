# Statement

## Problem Statement

Many people use weak passwords like "password123" or reuse the same
password on many apps. If one app gets hacked, attackers can log in
to all the other accounts too. Most people do not know whether their
password is strong, or how to improve it. This project builds a
simple tool that checks password strength, explains how to improve
it, and warns the user when the same password is reused.

## Scope of the Project

Included:

- Checking password strength for multiple apps in one session
- Giving a score, a rating (WEAK / MEDIUM / STRONG / VERY STRONG)
  and tips for improvement
- Detecting common passwords and easy patterns (like "123" or "abc")
- Detecting the same password used in more than one app
- Generating strong random password suggestions
- Logging events (without saving the actual passwords)

Not included:

- Storing passwords permanently
- Checking passwords against online data breach databases
- A graphical interface or website (it is a command-line tool)

## Target Users

- Students and beginners who want to learn about password safety
- Everyday users who want to check their own passwords
- Teachers or trainers who need a simple demo of password security

## High-Level Features

1. Password Strength Checker - scores a password out of 6 based on
   length, character types, repeated characters and easy patterns.
2. Feedback and Tips - tells the user exactly what to fix.
3. Reuse Detection - warns if one password is used in several apps.
4. Password Generator - suggests a strong random password using
   Python's secure `secrets` module.
5. Input Validation and Logging - handles empty or wrong input and
   records activity in a log file.
