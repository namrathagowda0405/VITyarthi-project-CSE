Project Overview:
This project is a modular Python library that implements a set of common number-theoretic and digit-manipulation functions. It is intended for students learning algorithm design and elementary number theory, and for developers who want a compact, well-documented utility package of small numeric algorithms (factorial, primality and factorization helpers, digit functions, sequence generators, etc.). Each function is implemented with clear input.
Key Features:
 factorial(n) — factorial of a non-negative integer, is_palindrome(n) — checks whether a number reads the same forwards and backwards, mean_of_digits(n) — returns the average of a number’s digits, digital_root(n) — repeatedly sums digits until a single digit remains, is_abundant(n) — returns True if sum of proper divisors of n > n, is_deficient(n) — returns True if sum of proper divisors of n < n, is_harshad(n) — checks if n is divisible by the sum of its digits, is_automorphic(n) — checks whether n² ends in the digits of n, is_pronic(n) — checks whether n is product of two consecutive integers, prime_factors(n) — returns list of prime factors of n, count_distinct_prime_factors(n) — counts unique prime factors, is_prime_power(n) — checks if n = p^k for prime p and integer k ≥ 1, is_mersenne_prime(p) — checks whether 2^p − 1 is prime (given p prime), twin_primes(limit) — generates twin prime pairs up to limit, num_divisors(n) — returns number of positive divisors of n, sum_of_divisors_less_than(n, m) — sum of proper divisors less than m, are_amicable(a, b) — checks whether a and b are amicable numbers, multiplicative_persistence(n) — counts steps to reduce a number by multiplying digits until a single digit and is_highly_composite(n) — checks if n has more divisors than any smaller positive integer.
 Technology & Tools Used:
Language: Python 3.10+ (recommended)
Testing: pytest
Packaging / Dependency management: pip, optional venv or virtualenv
Version control: git
Code quality tools (optional): flake8, black (formatter), mypy (optional static typing)
Development environment: any text editor or IDE (VS Code, PyCharm, etc.)
CI (optional): GitHub Actions for running tests on push/PR
Steps to install and run the project:
Clone the repository
Create and activate a virtual environment.
Install runtime and development dependencies.
Run example scripts or interactive demo
Instructions for testing:
Install test dependencies.
Run the full test suite.
Interpreting results.
Documentation & Usage Guidelines:
Each public function includes a docstring (parameters, return type, raised exceptions, and examples).
The README.md contains a quick start, list of principal functions, and contact/contribution information.
Use semantic versioning and include a changelog for releases.
Prefer small, well-tested functions with clear responsibilities.
License and Contribution Policy
Include a permissive license, e.g., MIT, in LICENSE.
Provide a CONTRIBUTING.md describing coding style, testing expectations, and PR workflow.
Require that contributions include unit tests for new behavior and pass CI checks before merging.



