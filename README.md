# Pranati-CSE-project
README file:

Library Book Finder – README
Project Title: Library Book Finder (Python)
Overview
The Library Book Finder is a simple Python-based application that helps users quickly locate books in a library based on their topic or subject area.
The user enters a topic, and the system displays all available books related to that topic.
This project demonstrates the use of Python dictionaries, functions, user input handling, and conditional logic.
Features
•	Search for books by topic
•	Predefined topics and book lists
•	User-friendly text-based interface
•	Error handling for invalid topics
•	Simple and easy-to-understand Python code
Technologies Used
•	Python 3.x

How to Run the Project:
1. Install Python
After that checking version:
python --version
2. Saving the Script
Create a file named:
library_book_finder.py
Paste the project code into it.
3. Running  the Program
Use the command:
python library_book_finder.py
4. Entering a Topic
Example inputs:
science
history
technology

Code Snippet
library = {
    "science": ["A Brief History of Time", "The Selfish Gene", "Cosmos", “relativity” , “H.C VERMA”,  “The double helix”,  “The origin of species”, “Sapiens: brief history of humankind”],
    "technology": ["Clean Code", "Introduction to Algorithms", "Python Crash Course", “Life 3.0”, “The Innovators by Walter Isaacson”, “Designing Data-Intensive Applications” ],
    "history": ["Sapiens", "Guns, Germs, and Steel", "The Silk Roads" , “the rise and fall of third reich ”, “the warmth of other sun” ],
    "literature": ["Pride and Prejudice", "Hamlet", "To Kill a Mockingbird", “the bluest book”, “The Secret History”, “The Brothers Karamazov”],
    "math": ["Calculus Made Easy", "Linear Algebra Done Right", "Introduction to Probability", “calculus the early transendentals” , ”Thomas calculus” ]
}

def find_books_by_topic(topic):
    topic = topic.lower()
    
    if topic in library:
        print(f"\nBooks available under '{topic.title()}' topic:")
        for book in library[topic]:
            print(" -", book)
    else:
        print("\nSorry! No books found under this topic.")

print("Welcome to the Library Book Finder")
user_topic = input("Enter a topic to search for books: ")
find_books_by_topic(user_topic)

Project Structure
>Library-Book-Finder
>library_book_finder.py
 README.md

Sample Output
 Welcome to the Library Book Finder
Enter a topic to search for books: science

Books available under 'Science' topic:
 - A Brief History of Time
 - The Selfish Gene
 - Cosmos
 - H.C VERMA
 - The double helix
 - The origin of species, etc
  
Future Enhancements
•	Add feature to insert new books dynamically
•	Store library data in JSON or database
•	Add GUI (Tkinter) interface
•	Search by author name
•	Advanced filtering (year, category, publication)
