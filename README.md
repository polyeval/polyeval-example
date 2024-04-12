# Polyeval-Example
An example of using `PolyEval` for evaluate programs of 8 mainstream programming languages: C#, C++, Go, Java, JavaScript, PHP, Python and Ruby.

# Usage

Requires `Nix` installed for reproduction of runtime environments:

```bash
$ git clone --recursive https://github.com/polyeval/polyeval-example
$ cd ./polyeval-example
$ nix-shell --pure
$ pdm install
$ pdm run python test_example_evaluation.py # Will execute example tests for 8 programming languagaes.
```