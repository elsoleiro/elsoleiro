Share beautiful code with me.

```scheme 
(define atom?
  (lambda (x)
    (and (not (pair? x)) (not (null? x)))))
    
(define lat?
  (lambda (l)
    (cond
      ((null? l) #t)
      ((atom? (car l)) (lat? (cdrl)))
      (else #f))))
      
; little schemer, d friedman. p16
```

Pins are current. Either books or work in progress.
