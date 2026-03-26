# pokedexcli-go
A high-performance, terminal-based Pokedex application built with Go. This project was developed as part of the Boot.dev backend track, focusing on efficient API consumption, custom caching mechanisms, and robust CLI architecture. A bit different than the course project in that this project is focused on Test-Driven Development.

## Features
- Interactive REPL: A smooth Read-Eval-Print Loop for real-time interaction.
- PokeAPI Integration: Real-time data fetching for locations, Pokemon species, and stats.
- Custom In-Memory Cache: A hand-rolled caching system with configurable reaping intervals to minimize network latency and API load.
- Pokemon Capture System: A specialized mechanic to "catch" and store Pokemon in a local Pokedex based on their base experience.
- Deep Inspection: Detailed view of caught Pokemon, including stats, types, and abilities.

## Installation
Make sure have go programming language installed. 

1. Clone this repo and navigate to the folder
```
#!/bin/bash
git clone https://github.com/rangga-prangwedana/pokedexcli-go.git
cd pokedexcli-go
```
2. Build
```
go build -o pokedex
```
3. Run
```
./pokedex
```
