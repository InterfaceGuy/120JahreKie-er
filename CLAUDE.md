# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview
This is a documentation repository for a 60th birthday escape room game project called "120 Jahre Kießer". The project is a collaborative puzzle game designed for 11 tables of players with interconnected mini-games forming a circular challenge structure.

## Repository Structure
- `docs/` - Main documentation directory containing all game design files
  - `concept_overview.md` - Game mechanics, structure, and overall design concept
  - `task_list.md` - Complete list of 11 interconnected puzzle tasks with solutions
  - `master_puzzle.md` - Final crossword puzzle that combines all task solutions
  - `player_guide.md` - Instructions and rules for game participants
- `media/` - Image assets for the puzzle tasks (11 images corresponding to each task)
- `120JahreKießer.key` - Keynote presentation file
- `context.jpg`, `notes.jpeg` - Reference materials

## Game Architecture
The escape room follows a circular structure where:
- 11 teams start at different tasks simultaneously
- Each task takes ~90 seconds to complete
- Teams send "ambassadors" to other tables to gather information
- All task solutions feed into a final crossword puzzle that reveals a 4-letter code
- The code unlocks access to table fireworks and opens the dessert buffet

## Key Design Elements
- **Interconnected Tasks**: Each puzzle requires information from other teams
- **Ambassador System**: Only one person per table can move between stations
- **Time Management**: Fast-paced 90-second intervals keep the game dynamic
- **Final Integration**: Master puzzle combines all individual solutions using specific letter positions

## Documentation Standards
- All tasks are numbered 1-11 in sequential order
- Each task includes the answer, responsible person, and associated image
- TODO items use markdown checkboxes for progress tracking
- German language is used throughout for the target audience

## Working with This Repository
When making changes:
- Maintain the circular game flow structure
- Ensure task numbering remains sequential (1-11)
- Keep solution times around 90 seconds per task
- Preserve the ambassador movement rules in all documentation
- Update the master puzzle if task solutions change