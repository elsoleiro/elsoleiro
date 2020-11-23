Share beautiful code with me.

```scheme 
(define lat?
  (lambda (l)
    (cond
      ((null? l) #t)
      ((atom? (car l)) (lat? (cdrl)))
      (else #f))))
      
; little schemer, d friedman. p16
```
