Share beautiful code with me.

```scheme 
(define atom?
  (lambda (x)
    (and (not (pair? x)) (not (null? x)))))
    
(define lat?
  (lambda (l)
    (cond
      ((null? l) #t)
      ((atom? (car l)) (lat? (cdr l)))
      (else #f))))
      
; d friedman, m felleisen
```
