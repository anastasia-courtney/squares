# squares

This project, originally submitted in partial fulfillment of the requirements for the Computer Science Tripos, is an effort to reduce the computational complexity to exhaustively Square the Square (and rectangles).

Squaring Squares and Rectangles describes decomposing them into distinct integer squares. Ian Gambini's 1999 work presented the first algorithm to produce SPSRs and SPSSs exhaustively, and in this project significant refactoring of the algorithm lead to an exponential reduction in complexity. Additionally, the new algorithm was parallelised to take advantage of modern machines.

[This repo is a reimplementation of the original project submitted in partial fulfillment of the requirements for the Computer Science Tripos](https://github.com/anastasia-courtney/squaring-the-square)

[The complete write-up is included, with intent to publish in the coming year.](./AC_MEng_Dissertation.pdf)

## Discoveries Made (Original Project)

In June 2023, the algorithm was run for 11 days across 9 cores, enumerating up to width 150, and produced the following discoveries:

- An exhaustive enumeration of all SPSSs, SPSRs, CPSSs, and CPSRs up to width 150, presented with notable properties such as order and boundary squares.
- 66 undiscovered SPSRs.
- Proof of the 10 smallest SPSRs of orders 17-26.
- Proof of the 8 smallest SPSRs with 5-12 boundary squares.
- An undiscovered and remarkable isomer:
  ![triple_readme drawio](https://github.com/anastasia-courtney/squaring-the-square/assets/60652829/37ea8882-6fa3-43d7-a9ad-f450277cb53b)
  - The smallest possible, and only the ninth to be discovered, isomer triple. 
  - The smallest possible, and first identified, isomer of order 22.
  - Demonstrates uncommon symmetry among isomers.
- A new bound on the number of 2-square edges a PSS can have.