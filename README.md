# Asteroids

A small arcade game built with Python and Pygame. Control a spaceship, shoot incoming asteroids, and avoid collisions. Larger asteroids split into smaller, faster fragments when hit; colliding with an asteroid ends the game.

Built while following the [Boot.dev Asteroids course](https://www.boot.dev/courses/build-asteroids-python). I wrote most of the implementation myself, working from the tutorial's requirements and guidance. The project gave me practical experience with object-oriented programming, game loops, vector-based movement, and collision detection.

## Run locally

Requires Python 3.13 and [uv](https://docs.astral.sh/uv/getting-started/installation/).

From the project directory, install the dependencies and start the game:

```bash
uv sync --locked
uv run main.py
```

## Controls

| Key | Action |
| --- | --- |
| W / S | Move forward / backward |
| A / D | Rotate left / right |
| Space | Shoot |

Close the game window to quit.

## Next steps

I plan to design and implement the following extensions independently, without step-by-step tutorial guidance.

1. Add a scoring system
2. Implement multiple lives and respawning
3. Add an explosion effect for the asteroids
4. Add acceleration to the player movement
5. Make the objects wrap around the screen instead of disappearing
6. Add a background image
7. Create different weapon types
8. Make the asteroids lumpy instead of perfectly round
9. Make the ship have a triangular hit box instead of a circular one
10. Add a shield power-up
11. Add a speed power-up
12. Add bombs that can be dropped
