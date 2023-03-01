# Chatbot(GPT-3) with Rust
This is a chat application implemented in Rust that uses the OpenAI GPT-3 language model to generate responses to user messages. The chat application is designed to be run locally and Minikube, and it provides a simple command-line interface for users to interact with.

## Installation
You will need to obtain an API key from OpenAI in order to use the GPT-3 language model. Once you have obtained an API key, you should store it in the `OAI_TOKEN` environment variable on your system. The use of the OpenAI GPT-3 language model requires an API key, which must be obtained separately from OpenAI (free trial is provided). The project's main.rs file assumes that this key is stored in the `OAI_TOKEN` environment variable.

To install and run the Rust Chat GPT Project, follow these steps:
1. Clone the project repository
```
git clone https://github.com/Mushroom-Wang/IDS721-PJ2-Final
```
1. Change into the project directory
```
cd chatgpt
```
1. Set the `OAI_TOKEN` environment variable in `.env`
```
OAI_TOKEN = <your_api_key>
```
1. Run the project
```
cargo run
```

## Features
 - Define a struct to represent API requests.
 - Define a struct to represent API responses.
 - Create a Rust vector to hold the available choices for the chat application.
 - Implement a tokio-based asynchronous main function to run the chat application.
 - Load environment variables for the chat application, including the API key and port number.
 - Use the Hyper Rust library to create an HTTP connector for the chat application.
 - Create a client struct to handle HTTP requests and responses for the chat application.
 - Set the API URL to which the chat application will send requests.
 - Display a prompt to the chat operator to enter a message or make a selection.
 - Include an authentication token in the header of API requests from the chat application.
 - Set up a loop to read user input and send requests to the chatbot API.
 - Display a spinner or progress indicator while waiting for a response from the API.
 - Send a request to the chatbot API for every user input received in the chat application.
 - Display the generated response from the chatbot API in the chat application.

## 

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
