# COVID_TRACER

COVID_TRACER is a C++ application designed to simulate a contact tracing system for COVID-19. It allows users to input their information, establish connections with other individuals, and assess the risks of infection based on their contact history.

## Files

- `Tracer.h`: Header file containing the declaration of the `Tracer` class and its member functions and variables.
- `Tracer.cpp`: Implementation file for the `Tracer` class, containing the logic for managing users and their connections, as well as algorithms for finding the shortest path to an infected individual.
- `main.cpp`: Contains the main function and the user interface logic for interacting with the system.

## How to Run

1. Ensure you have a C++ compiler installed (e.g., g++, clang++).
2. Navigate to the project directory.
3. Compile the project using the command: `g++ -o COVID_TRACER Tracer.cpp main.cpp`
4. Run the compiled executable using the command: `./COVID_TRACER`

## Dependencies

- Standard Template Library (STL)

## Contributing

If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.



