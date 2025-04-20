# Stick Fighter

A vibe-coded browser-based fighting game. Like Street Fighter, but with stick figures. Supports both singleplayer (vs the computer) and multiplayer.

Play at https://aaronchelvan.github.io/stickfighter.

## Controls

### Player 1 (Blue)
- `A` - Move left
- `D` - Move right
- `W` - Jump
- `S` - Duck
- `Z` - Punch
- `X` - Kick
- `C` - Shoot Fireball

### Player 2 (Red)
- `←` - Move left
- `→` - Move right
- `↑` - Jump
- `↓` - Duck
- `,` - Punch
- `.` - Kick
- `/` - Shoot Fireball

## Game Rules

- Each player starts with 100 health
- Punches deal 10 damage
- Kicks deal 15 damage
- Fireballs deal 20 damage
- Players can dodge all attacks by ducking
- Fireballs have a longer cooldown than melee attacks
- First player to win 2 rounds wins the game
- A round is won when the opponent's health reaches 0

## Technical Details

The game is built using vanilla JavaScript and HTML5 Canvas. No external dependencies are required.

## Music

Generated with https://suno.com/

## TODO
- Add block
- Improve computer AI
- Improve player animations
- More worlds