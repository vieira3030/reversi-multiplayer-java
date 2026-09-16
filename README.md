# Reversi Multiplayer

A networked multiplayer implementation of Reversi (Othello), built in Java with a JavaFX interface and TCP socket communication for real-time play between two clients.

## Features
- Full Reversi rule set (move validation, piece flipping, win detection)
- Real-time two-player matches over TCP sockets
- Save and load game state
- JavaFX graphical interface

## Tech Stack
Java · JavaFX · TCP Sockets

## Architecture
The game logic is split across 7 classes:
- `Jogo` — game loop and turn management
- `Tabuleiro` — board state
- `Jogador` — player data
- `Regras` — move validation and rules
- `CorPeca` — enum for piece color (PRETO, BRANCO, VAZIO)
- `App` — JavaFX entry point
- `GestorRede` — network communication between clients

## How to Run
```bash
git clone https://github.com/vieira3030/reversi-multiplayer-java.git
cd reversi-multiplayer-java
mvn javafx:run
```

## Status
Completed · Academic project for Programming Laboratory, ESTG - UNIPVC (2026)

## Authors
Rodrigo Vieira · Rodrigo Malheiro
