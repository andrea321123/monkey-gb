# monkey-gb

Gameboy emulator written in Kotlin.

## Screenshots

![Tetris](images/tetris.png)
![Super Mario Land](images/Super-Mario-Land.png)

## Building

1. Clone the repo:

```sh
git clone https://github.com/andrea321123/monkey-gb
cd monkey-gb
```
2. Compile with Gradle:

```sh
./gradlew build

```

## Usage

Run with Gradle:
```sh
./gradlew run --args="[ROM file]"
```
where [ROM file] is the name of the ROM we want to run.

## Screenshots

![Kirby's Dream Land](images/Kirby's-Dream-Land.png)
![Bubble ghost](images/Bubble-ghost.png)

## Issues

The emulator has issues running some games; furthermore, MBC3 memory banking and sound aren't implemented yet.
