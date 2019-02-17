# tpl
Yasu's notes on Types and Programming Languages

Section 3.5 Evaluation, p 35
```
... for example, the term

if true then (if false then false else false) else true

does not evaluate to if true then false else true.  Our only choice is to
evaluate the outer conditional first, using E-If.
```

I don't know why E-If.  The term true does not seem to fit the premise of the rule E-If.
