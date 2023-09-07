
# BCD Questions

## Question 2.1

- All number-strings that have the value 42:
  - `(^42$)`
- All number-strings that do not have the value 42:
  - `^(?!42(?!.)).*`
- All number-strings that have a value that is strictly greater than 42:
  - `^(?!([0-9]|[0-3][0-9]|40|41|42)(?!.)).*`

## Question 2.2

Given the regular expression `a∗(a|b)aa:`

- Construct an equivalent NFA using the method in section 2.4:
  - ![NFA Diagram](NFA.svg)
- Convert this NFA to a DFA using algorithm 2.3
  State | a | b | go to
  ---|---|---|---
     s0 | {} | {} | {}
     s1 | {} | {} | {}
  - ![DFA Diagram](DFA.svg)
