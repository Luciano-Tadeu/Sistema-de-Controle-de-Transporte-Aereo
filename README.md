# Air Transport Management System - Flight Data Manager - AED2

Information system for air transport management developed as a Practical Assignment for the **Algorithms and Data Structures II** course (UFMT).

## 🛠 Project Structure

The project follows the required directory hierarchy:

* **/implementacao** (implementation): C source code modularized by ADTs (Abstract Data Types) using `.h` and `.c` files.
* **/dados** (data): Persistence files (`.csv`) for records, users, and logs.
* **/testes** (tests): Test cases (TC) for automated execution.
* **/saida** (output): `saida.csv` file for persisting query results.

## 🚀 Compilation and Execution

To compile the project on Linux using `gcc`:

```bash
cd implementacao
gcc -o programa programa.c logs.c dados.c autenticacao.c -Wall
