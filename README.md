# sicp

## syntax examples

if / else (from 1.1.6)

```
(define (abs x)
(cond ((> x 0) x)
      ((= x 0) 0)
      ((< x 0) (- x))))
```

```
(cond ((< x 0) (- x))
       (else x)))
```

```
(if (> b a) b a)
```