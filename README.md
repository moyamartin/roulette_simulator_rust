# roulette_simulator_rust
Rustlette: a roulette simulator based in Rust!

# Pre-commit config

The aim of this configuration is to have some automatic code format check
every time we run the git commit command.


- Install pre-commit:

  ```
  pip install pre-commit
  ```

- Update the repositories:

  ```
  pre-commit autoupdate
  ```

- Install the git hooks:

  ```
  pre-commit install
  ```

Now every time you run git commit you should have an automatic code format
check on every staged file. If the pre-check fails black will automatically
format the py files. You must add the black changes and commit again in order
to actually commit your changes.
