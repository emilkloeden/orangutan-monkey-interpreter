# Orangutan Monkey Interpreter

![Orangutan Monkey Interpreter logo](./assets/logo.png)

The Orangutan Monkey Interpreter is an interpreter that executes code written in Thorsten Ball's [Monkey language](https://monkeylang.org/) written in the [Orangutan programming language](https://github.com/emilkloeden/orangutan) itself an implementation and extension of Monkey.

## Features

A "feature-complete"^ implementation of [Monkey](https://monkeylang.org/) written in a superset of monkey. Repository includes two scripts to execute:

- single Monkey scripts:
  `orangutan run .\src\monkey-run.utan my-script.monkey`

- multiple Monkey programs via a Read-Evaluate-Print-Loop (REPL):
  `orangutan run .\src\monkey-repl.utan`

^ well at least it tries to be, there are likely bugs at this early stage.

## Installation

1. Clone the repository:

```bash
   git clone https://github.com/emilkloeden/orangutan-monkey-interpreter.git
   cd orangutan-monkey-interpreter
```

2. Ensure you have the [Orangutan language](https://github.com/emilkloeden/orangutan) installed and properly configured on your system.

## Usage

Open a Monkey REPL to execute Monkey programs:
`orangutan run .\src\monkey-repl.utan`

Or run a single script to execute Monkey scripts:
`orangutan run .\src\monkey-run.utan my-script.monkey`

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
