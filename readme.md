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
      
; d friedman, m felleisen
```

Pins are current. Either books or work in progress.
```
[flash-cards](https://github.com/elsoleiro/flash-cards)
revising tool with a sqlite db:
- registration/login system
- bcrypt hashing, werkzeug_security, flask UserMixin
- custom json encoder to pass list of objects over to js models.py line 58-94.
- async function to update status of card -- boolean field in sqlite db "known" -- on button press. app.js lines 60-74.
- scrap project to implement and deploy in react.
```
```
[chartjs-dashboard](https://github.com/elsoleiro/chartjs_dashboard)
things get weird, i leverage pandas to append information to a csv which is displayed by ChartJS. allows for modification of csv data.
- login system
- bcrypt hashing
```
