# Library book finding -
library = {
    "science": ["A Brief History of Time", "The Selfish Gene", "Cosmos", “relativity” , “H.C. VERMA”,  “The double helix”,  “The origin of species”, “Sapiens: brief history of humankind”],
    "technology": ["Clean Code", "Introduction to Algorithms", "Python Crash Course", “Life 3.0”, “The Innovators by Walter Isaacson”, “Designing Data-Intensive Applications” ],
    "history": ["Sapiens", "Guns, Germs, and Steel", "The Silk Roads" , “the rise and fall of third reich ”, “the warmth of other sun” ],
    "literature": ["Pride and Prejudice", "Hamlet", "To Kill a Mockingbird", “the bluest book”, “The Secret History”, “The Brothers Karamazov”],
    "math": ["Calculus Made Easy", "Linear Algebra Done Right", "Introduction to Probability", “calculus the early transendentals” , ”Thomas calculus” ]
}

def find_books_by_topic(topic):
    topic = topic.lower()  # Normalize input
    
    if topic in library:
        print(f"\nBooks available under '{topic.title()}' topic:")
        for book in library[topic]:
            print(" -", book)
    else:
        print("\nSorry! No books found under this topic.")

# Main program
print("Welcome to the Library Book Finder")
user_topic = input("Enter a topic to search for books: ")

find_books_by_topic(user_topic)
