# Bouncing Ball Game

This is a simple Rust program that simulates a bouncing ball within a frame. The ball moves and bounces off the walls of the frame. 

## Project Structure

- **VertDir**: Enum to represent vertical direction (Up or Down).
- **HorizDir**: Enum to represent horizontal direction (Left or Right).
- **Ball**: Struct to represent the ball with position and direction.
- **Frame**: Struct to represent the frame with width and height.
- **Game**: Struct to represent the game state containing the frame and the ball.


## How to Run
Ensure you have Rust installed. If not, download and install from rust-lang.org.
Clone this repository.
Navigate to the project directory.
Run the project using cargo run.

$ cargo run

Output
The program will print the frame with the ball bouncing around. The ball is represented by 0, vertical walls by |, and horizontal walls by -.
