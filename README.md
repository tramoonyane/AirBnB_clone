AirBnB Clone - Console

This project is the initial step towards building an AirBnB clone. The goal is to create a command-line interpreter to manage AirBnB objects, implement a parent class (BaseModel) for initialization and serialization, and develop a file storage engine for saving and loading data.

Project Overview

- BaseModel:
  - Handles initialization, serialization, and deserialization of instances.
  - Converts instances to dictionaries and JSON strings, and vice versa.

- AirBnB Classes:
  - Classes for various AirBnB objects (User, State, City, Place, etc.) that inherit from BaseModel.

- File Storage Engine:
  - Saves instances to a file and loads them back.
  - Uses JSON format for storing serialized data.

- Command Interpreter:
  - Allows users to interact with AirBnB objects via the command line.
  - Supports commands for creating, updating, deleting, and displaying instances.
  - Includes commands for saving and loading data.

- Unit Tests:
  - Validates functionality of classes and storage engine.

How to Use

1. Install Dependencies:
   bash
   Install any necessary dependencies
   pip install -r requirements.txt

