# Python Hello World
A simple "Hello, World!" program in Python.

## How to Build
To build the program, follow these steps:

1. Clone the repository.
2. Open a terminal or command prompt and navigate to the directory where your Python code is saved.
3. Type the following command to run your program:
```bash
python3 main.py
```
This will run your Python code and you should see the output "Hello, World!" in the terminal.

## Using Docker
To run the program using Docker, follow these steps:

1. Open a terminal or command prompt and navigate to the directory where your program is saved.

2. Type the following command to build a Docker image of your program:
```perl
docker build -t my-python-app .
```
This will create a Docker image named my-python-app from your Dockerfile and Python code in the current directory.

3. To run the Docker container, type the following command:

```perl
docker run my-python-app
```
This will run the my-python-app Docker container and you should see the output "Hello, World!" in the terminal.

Contributions
Contributions are welcome! If you find a bug or would like to suggest an improvement, please create a new issue or submit a pull request.
