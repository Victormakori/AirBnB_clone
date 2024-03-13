# AirBnB Clone Command Interpreter

## Background Context

Welcome to the AirBnB clone project! Before diving into the code, please make sure to familiarize yourself with the AirBnB concept page.

## First Step: Command Interpreter

This project aims to develop a command interpreter to manage AirBnB objects. It serves as the foundation for building a full web application, the AirBnB clone. The command interpreter plays a crucial role in integrating various components such as HTML/CSS templating, database storage, API, and front-end integration.

### Objectives

- Implement a parent class (BaseModel) responsible for initialization, serialization, and deserialization of future instances.
- Establish a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file.
- Define classes for AirBnB objects (User, State, City, Place, etc.) inheriting from BaseModel.
- Develop the initial abstracted storage engine: File storage.
- Create comprehensive unit tests to validate all classes and the storage engine.

## What's a Command Interpreter?

The command interpreter, reminiscent of the Shell, is a tool designed for managing objects within our project. It facilitates various operations, including:

- Creating new objects (e.g., User, Place)
- Retrieving objects from files, databases, etc.
- Performing operations on objects (counting, computing stats, etc.)
- Updating attributes of objects
- Deleting objects

This README serves as a guide to understanding the purpose and implementation of the AirBnB clone's command interpreter. Feel free to explore the codebase and contribute to the project's development. Happy coding!

