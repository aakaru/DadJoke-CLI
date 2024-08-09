# DadJoke CLI

DadJoke CLI is a command-line interface (CLI) application built with Go, leveraging the powerful Cobra library. This tool allows users to fetch and enjoy a random dad joke right in their terminal, providing a quick dose of humor whenever needed. The jokes are sourced from the popular [icanhazdadjoke API](https://icanhazdadjoke.com/), which hosts a vast collection of dad jokes, known for their light-hearted and punny nature.

Whether you're looking to add a bit of fun to your day, entertain your friends, or even just test out your CLI skills, DadJoke CLI is designed to be a simple yet delightful tool. It's easy to set up, straightforward to use, and guarantees a smile with every command.

## Features

- **Random Joke Fetching**: Retrieves a random dad joke from the icanhazdadjoke API with a single command.
- **User-Friendly**: Simple command structure using Cobra, making it accessible even for those new to CLI tools.
- **Cross-Platform Compatibility**: Built with Go, ensuring it runs smoothly on various operating systems including Linux, macOS, and Windows.
## Installation

### Prerequisites

- Go (1.16 or later) installed on your system.
- Cobra 

### Clone the Repository

```bash
git clone https://github.com/yourusername/dadjoke-cli.git
cd dadjoke-cli
```

## Build the CLI Tool

```bash
go build -o dadjoke-cli
```
This will create an executable named dadjoke-cli in the root of the project.

## Usage

 Get a Random Dad Joke
 Run the following command to fetch and display a random dad joke:
 
```bash
./dadjoke-cli random
```

## Contributing

If you want to contribute to this project, please fork the repository and submit a pull request with your changes. Contributions and suggestions are welcome!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- icanhazdadjoke API for providing the jokes.
- Cobra for the CLI library.




