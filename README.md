# PokedexCLI

This project is a command-line REPL (Read-Eval-Print Loop) Pokedex built in Go. It uses the [PokeAPI](https://pokeapi.co/) to fetch data about Pokémon and allows users to interact with it in real-time. This project will help you practice Go skills such as making network requests, handling JSON data, and implementing caching to optimize performance.

## Features

- **REPL Environment**: A simple interactive command-line environment where users can input commands and receive real-time feedback.
- **PokeAPI Integration**: Fetch Pokémon data from PokeAPI, including details like type, abilities, and stats.
- **Caching**: Store previously fetched Pokémon data to reduce the number of API requests and improve performance.
- **JSON Handling**: Parse and handle JSON responses from the API.

## Tools and Libraries

- **Go**: The main programming language for building the REPL and handling API requests.
- **PokeAPI**: The external API used to retrieve Pokémon information.
- **net/http**: Go's standard library for making HTTP requests.
- **encoding/json**: For parsing and working with JSON data in Go.

## How to Run

1. Clone the repository.
2. Make sure you have Go installed with ```go version```
3. Run the REPL using the following command:
```./pokedexcli```
- Type the ```help``` command. They will prints a help message describing how to use the REPL.
