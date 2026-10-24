# Antenna Network Manager

A C application that models antenna connections using **graphs and linked lists**, with insertion, removal, and cost analysis operations. Developed as coursework for **Advanced Data Structures**.

## Technologies

- C
- GCC and GNU Make
- Doxygen documentation
- LaTeX project report

## Getting started

### Requirements

Use GCC, GNU Make, and a shell with `mkdir` and `rm`, such as Linux, WSL, or a compatible Unix environment. Run the following commands from the repository root so the supplied input file remains accessible.

```sh
git clone https://github.com/rpinheiror/MAIN-Repository.git
cd MAIN-Repository
make
make run
```

The Makefile builds `bin/main` from the C files in `src/`. The sample input is provided in [`antenas.txt`](antenas.txt).

To remove the compiled objects and executable:

```sh
make clean
```

## Repository structure

| Path | Purpose |
| --- | --- |
| [`src/`](src/) | C source code and application entry point |
| [`include/`](include/) | Headers, data structures, graph and linked-list interfaces |
| [`antenas.txt`](antenas.txt) | Sample antenna data |
| [`Makefile`](Makefile) | Build, run, and cleanup targets |
| [`doc/`](doc/) | Project report and documentation |
| [`doxdoc/`](doxdoc/) | Doxygen documentation |
| [`Projeto_EDA.pdf`](Projeto_EDA.pdf) | Assignment specification |

## Documentation

The original coursework materials and code identifiers are in Portuguese. See the project report in `doc/` and the API documentation in `doxdoc/` for additional detail.

## Author

**Rodrigo Henrique Silva Pinheiro** — student no. 31502.
