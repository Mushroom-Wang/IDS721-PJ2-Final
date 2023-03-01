# Chatbot(GPT-3) with Rust


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

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
