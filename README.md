# Elixir Identicon Generator

This Elixir project generates unique identicon images based on input strings. An identicon is a visual representation of a hash value, often used as default user profile pictures.

## Features

- Generates a unique identicon for any input string
- Uses MD5 hashing to ensure consistency
- Creates a 250x250 pixel image
- Saves the generated image as a PNG file

## Setup and Usage

- Clone this repository
- Install Erlang and Elixir\
  (versions are in .tool-versions, or you can just install using `asdf` or `mise`)
- Run this to get dependencies and compile:

  ```bash
  mix deps.get
  mix compile
  ```

- Run the code with IEX:

  ```bash
  iex -S mix
  ```

- Generate the identicon for "example" string by running `Identicon.main("example")` in IEX.\
  The PNG image file should be generated in the project root directory.
