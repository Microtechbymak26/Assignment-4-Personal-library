# Library Manager

This is a simple library manager program that helps you organize your books.

## Features

- Add books
- Remove books
- Search books
- View all books
- View library statistics

## Usage

1. **Adding a Book**
   - Select option 1 from the menu
   - Enter book title, author, year, genre, and reading status

2. **Removing a Book**
   - Select option 2 from the menu
   - Enter the title of the book to remove

3. **Searching Books**
   - Select option 3 from the menu
   - Choose search method (title or author)
   - Enter search term

4. **Viewing All Books**
   - Select option 4 from the menu
   - View list of all books

5. **Viewing Statistics**
   - Select option 5 from the menu
   - View total books and percentage of books read

## Data Storage

Book data is stored in the `library.txt` file. Each book contains the following information:
- Title
- Author
- Year
- Genre
- Reading status (read/unread)

## Requirements

- Python 3.x
- No additional packages required

## How to Run

1. Open terminal
2. Navigate to the program directory
3. Run the following command:
   ```
   python library-manager.py
   ``` 