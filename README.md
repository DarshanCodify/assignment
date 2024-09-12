# assignment

Question 1: By default are django signals executed synchronously or asynchronously? Please support your answer with a code snippet that conclusively proves your stance. 
The code does not need to be elegant and production ready, we just need to understand your logic.

Question 2: Do django signals run in the same thread as the caller? Please support your answer with a code snippet that conclusively proves your stance. 
The code does not need to be elegant and production ready, we just need to understand your logic.

Question 3: By default do django signals run in the same database transaction as the caller? Please support your answer with a code snippet that conclusively proves your stance.
The code does not need to be elegant and production ready, we just need to understand your logic.

1 Ans:Django signals are executed synchronously by default.

2 Ans:Yes, django signals run in the same thread as the caller by default.

3 Ans:Yes, django signals run in the same database transaction as the caller by default.
