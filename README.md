# Python Library Manager

A simple command-line application built in Python to practice managing inventory data using nested dictionaries and sets.

## Why I Built This

I built this project to transition from basic variable storage to handling structured, dynamic data in Python. As a beginner, I wanted to practice:
- Working with nested dictionaries to store multi-attribute data (author, availability status).
- Using Python `set` collection types to track unique genres automatically without duplicates.
- String normalization (`.strip()`, `.lower()`, `.title()`) to keep inventory lookups consistent regardless of user capitalization.

## Features

- **Catalog Management:** Add new titles with metadata or remove existing books from the library.
- **Unique Genre Tracking:** Automatically collects unique genres using a Python set.
- **Inventory Display:** View total library count, book details, and current shelf availability.
- **Input Normalization:** Cleans up user text inputs to prevent duplicate entries caused by casing differences.

## How to Run

1. Clone the repository and navigate into the directory:
   ```bash
   git clone [https://github.com/john-fafunmi/python-library-manager.git](https://github.com/john-fafunmi/python-library-manager.git)
   cd python-library-manager
