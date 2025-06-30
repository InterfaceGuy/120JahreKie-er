# 120 Jahre Kießer - Interactive Birthday Escape Room Game

A collaborative puzzle game designed for a 60th birthday celebration featuring 11 interconnected mini-games, team cooperation, and a circular challenge structure.

## Game Overview

This escape room game creates an engaging group experience where 11 teams work simultaneously on different puzzle stations, requiring cooperation and information sharing to solve a master puzzle and unlock the final celebration.

### Key Features
- **11 Interconnected Puzzles**: Each task requires information from other teams
- **Ambassador System**: Teams send representatives to gather information from other stations  
- **Fast-Paced Gameplay**: 90-second intervals keep the game dynamic
- **Circular Structure**: Teams rotate through all puzzles in sequence
- **Collaborative Victory**: All teams work together toward a shared goal

### Game Flow
1. 11 teams start at different numbered stations simultaneously
2. Each team solves their assigned puzzle (~90 seconds each)
3. Teams send "ambassadors" to other stations to gather required information
4. After completing all 11 puzzles, teams collaborate on the master crossword puzzle
5. The final 4-letter code unlocks the celebration (fireworks trigger + dessert buffet)

## How to Set Up Your Own Version

### Materials Needed
- **Puzzle Cards**: 11 different puzzle tasks + 1 master puzzle card
- **Images**: 11 corresponding images for each puzzle (provided in `media/` folder)
- **Tables**: 11 stations for teams to work at
- **Final Prize**: Something to unlock with the 4-letter code (GABE = 7-1-2-5)

### Setup Steps

#### 1. Prepare the Puzzle Materials
```bash
# Print puzzle cards (recommended: half-page A4 format)
# You'll need 12 sets total (11 + 1 backup)
# Each set contains:
- 11 individual puzzle cards
- 1 master puzzle card
```

#### 2. Customize the Puzzles for Your Event
Edit the files in the `docs/` directory to personalize for your celebration:
- `task_list.md` - Update the 11 puzzles with your own questions and answers
- `master_puzzle.md` - Adjust the crossword to use your new answers
- Replace images in `media/` folder with relevant photos

#### 3. Physical Setup
- **Station Layout**: Arrange 11 tables in a circle or accessible pattern
- **Materials per Station**: 
  - One puzzle card set per table
  - Pens/pencils for teams
  - Optional: timer visible to all teams
- **Game Master Station**: Central location to monitor progress and provide hints

#### 4. Team Organization
- **Team Size**: 4-6 people per table works best
- **Ambassador Rules**: Only one person per team can visit other tables
- **Starting Positions**: Assign each team a number (1-11) corresponding to their starting puzzle

### Game Master Instructions

#### Pre-Game
1. Explain the ambassador system (only one person moves between tables)
2. Distribute puzzle cards to each table
3. Set 90-second timer intervals for puzzle rotations
4. Clarify that teams should help each other when visited

#### During Play
- Monitor time and signal transitions
- Provide hints if teams get stuck (keep solutions simple)
- Ensure ambassador rule is followed
- Prepare final master puzzle distribution

#### End Game
- Distribute master puzzle when all teams finish individual tasks
- Guide teams through the crossword collaboration
- Reveal the final code and unlock your celebration!

## File Structure

```
├── README.md              # This file
├── CLAUDE.md             # AI assistant instructions
├── docs/
│   ├── concept_overview.md    # Game mechanics and design
│   ├── task_list.md          # All 11 puzzle tasks with solutions
│   ├── master_puzzle.md      # Final crossword puzzle
│   └── player_guide.md       # Instructions for participants
├── media/                    # Images for each puzzle task
└── 120JahreKießer.key       # Presentation file
```

## Customization Tips

### Adapting for Your Event
- **Personal Stories**: Replace biography-based questions with stories from your celebrant
- **Guest Knowledge**: Assign questions to people who know the answers
- **Cultural Context**: Adapt language and references for your audience
- **Difficulty Level**: Aim for 90-second solve times to maintain game pace

### Scaling the Game
- **Fewer Players**: Combine puzzles or reduce total number of stations
- **More Players**: Add additional teams at existing stations
- **Different Occasions**: Adapt puzzle themes for weddings, anniversaries, corporate events

## Technical Notes

The master puzzle creates the code **GABE** which converts to **7-1-2-5** using alphabet positions (G=7, A=1, B=2, E=5). Customize this final code for your specific celebration needs.

## Credits

Original game design for a 60th birthday celebration featuring collaborative puzzle-solving and social interaction mechanics.