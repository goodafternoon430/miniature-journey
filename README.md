# miniature-journey
QUANTA is a tiny quantum circuit simulator written in Python. The goal of QUANTA, as the title suggests, is to present quantum computing without using linear algebra. Instead, QUANTA represents a quantum state as a dictionary and applies operations in a functional style, using map, filter, reduce, etc.
technical details
For all technical details and an introduction to quantum computing without the linear algebra, see the accompanying paper.

structure
The state.py file contains the State class, which is a quantum state and supports a number of operations (Clifford + T).
There are example circuits in the examples/ folder.
usage
The easiest way to use QUANTA is with uv. To run an example, simply:

uv run examples/epr.py
citation
@misc{cryptoeprint:2025/1091,
      author = {Aws Albarghouthi},
      title = {Quantum Computing without the Linear Algebra},
      howpublished = {Cryptology {ePrint} Archive, Paper 2025/1091},
      year = {2025},
      url = {https://eprint.iacr.org/2025/1091}
}
