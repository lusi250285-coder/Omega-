# Pyramid H Language - لغة هرم H

Conceptual & Constructive Framework for studying primes.

## Idea
No actual infinity. Pyramid H grows step by step.
H_0 = {1}, H_{n+1} = H_n U {n+1}
L_0 = 10, L_{k+1} = 10^{L_k}

## Bridge Metric
For n, bridge d, 0 <= d < n, (n-d) and (n+d) prime.

## Empirical Results
- H_10: 2 bridges, smallest d=3 -> (7,13), largest d=7 -> (3,17)
- H_100: 8 bridges, smallest d=3 -> (97,103), largest d=97 -> (3,197)
- H_1000: 37 bridges, smallest d=9 -> (991,1009), largest d=997 -> (3,1997)

## Run
python pyramid_h.py

## Author
Fadwa (2026)
