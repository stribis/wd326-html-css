# 05 - Native Validation Pass

## Goal

Add constraints that match the booking requirements and make native validation
states understandable without JavaScript.

## Tasks

1. Require name, email, ticket type, visit date, guest count, and message.
2. Use `type="email"` for basic email syntax validation.
3. Limit the visit date to the supplied event weekend.
4. Set guest count to a minimum of 1, maximum of 6, and step of 1.
5. Require the message to contain between 20 and 300 characters.
6. Connect the message hint with `aria-describedby`.
7. Style `:user-invalid` and `:user-valid` without marking untouched fields red.

## Completion Check

Try empty, too-short, out-of-range, and valid submissions. Read each browser
message and decide whether the constraint helps the user recover.
