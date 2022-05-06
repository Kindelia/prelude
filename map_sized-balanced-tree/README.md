# Map sized Balanced Tree

This code uses the original implementation used in Haskell [Data.Map](https://hackage.haskell.org/package/containers-0.4.0.0/docs/Data-Map.html)

I highly suggest you, dear user that want to use a Map structure, to use code as documentation.

# Rewrites Count

Using HVM `master` branch

| n     | rewrite |
| ----- | ------- |
| 1     | 11      |
| 10    | 1236    |
| 100   | 34255   |
| 1000  | 619044  |
| 10000 | 9112107 |

Using HVM `quadratic fix` branch

| n     | rewrite |
| ----- | ------- |
| 1     | 11      |
| 10    | 1234    |
| 100   | 34250   |
| 1000  | 619036  |
| 10000 | 9112096 |
