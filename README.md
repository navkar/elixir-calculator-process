# Calculator - Elixir Process Demo

**A Elixir process demonstration**

## How to compile

```zsh
navkar@Naveens-MacBook-Pro repos % cd calculator-process 
navkar@Naveens-MacBook-Pro calculator-process % iex -S mix
```
## Elixir process demonstration

* Notice how the value of the calculator changes over time after the operations

```zsh
iex(1)> pid = Calculator.start
#PID<0.134.0>
iex(2)> Calculator.add(pid,200)
200
iex(3)> Calculator.sub(pid,10) 
190
iex(4)> Calculator.mul(pid,1000)
190000
iex(5)> Calculator.add(pid,1000)
191000
iex(6)> Calculator.add(pid,1000)
192000
iex(7)> Calculator.add(pid,1000)
193000
iex(8)> Calculator.div(pid,1000)
193.0
iex(9)> 

```

## HOW TO create a new MIX project

```bash
navkar@Naveens-MacBook-Pro repos % mix new calculator
* creating README.md
* creating .formatter.exs
* creating .gitignore
* creating mix.exs
* creating lib
* creating lib/calculator.ex
* creating test
* creating test/test_helper.exs
* creating test/calculator_test.exs

Your Mix project was created successfully.
You can use "mix" to compile it, test it, and more:

    cd calculator
    mix test

Run "mix help" for more commands.
```
