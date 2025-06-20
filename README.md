# Suzume's Adventure: Data Structure Final Project

This is a Java-based academic project created for **WIA1002 Data Structure** during Semester 2, 2022/2023 at Universiti Malaya. The project is a combination of **pathfinding algorithms**, **game logic (Tic-Tac-Toe variants)**, and **GUI/UX design** that simulate Suzume’s journey through a map filled with strategic puzzles and challenges.

---

## Project Overview

A teenager named **Suzume** is on a mission to save her country. She must:
- Decode grayscale map images to uncover paths.
- Solve pathfinding problems using DFS and BFS.
- Play multiple Tic-Tac-Toe variants to progress through stations.
- Experience checkpoint mechanics, scorekeeping, and real-time decision-making.

---

## Core Features

### 🔹 Part A: Map Deciphering
- **Image Reading & Conversion** using Java’s `ImageIO`.
- **Map Formation** from 4 separate images using BFS.
- **Pathfinding** with:
  - `dfs()` for paths with exactly 4 stations.
  - `bfs()` for shortest path traversal.
- **Shortest Path Detection** with custom algorithms.
- **Answer Decryption** for validation using encoded clues.

### 🔹 Part B: Game Mechanics
Three variations of Tic-Tac-Toe were implemented:
1. **5x5 Regular TTT**
2. **Reverse TTT**
3. **Treble Cross TTT** with Nim Game logic

Each game includes:
- AI engine with Easy, Medium, and Hard modes
- Minimax algorithm with alpha-beta pruning
- Move stack for undo functionality
- PVE and PVP modes
- Save/load functionality via serialization

### 🔹 Part C: Journey Simulation
- Suzume starts from the top-left and travels through stations.
- Loses a game? She returns to her last **checkpoint** (stack).
- Wins all station challenges to reach the destination and complete her mission.

---

## Algorithms & Data Structures

- **DFS & BFS** for pathfinding
- **Stack** for checkpoint management
- **Minimax** (with alpha-beta pruning) for AI engine
- **Serialization** for saving/loading state
- **File I/O** for leaderboard and user management
- **Nim Addition** strategy in Treble Cross TTT

---

## Engine Logic (AI Difficulty)

- **Easy:** Randomized moves
- **Medium:** Win-block-win logic
- **Hard:** Full Minimax with pruning

---

## Game Flow

1. Read and decode the grayscale maps.
2. Traverse the maps while solving TTT challenges.
3. Return to previous checkpoint if a game is lost.
4. Complete all stations and reach the destination.


