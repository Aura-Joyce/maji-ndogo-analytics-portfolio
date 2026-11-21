# Maji Ndogo – Python Short Course 2

# Project Overview

This project was part of my Python short course, where I worked with agricultural survey data from the Maji Ndogo farm survey. The course helped me understand how Python can be used to solve practical problems, organise data, improve program efficiency, and build reusable applications.

I worked through three main notebooks covering algorithm efficiency and Object-Oriented Programming (OOP).

# 1. Business Problem

The Maji Ndogo agricultural survey contains thousands of farm records, including field identification numbers, pollution levels, plot sizes, crop types, and harvest information.

The main challenges were:

- Finding information about a particular farm quickly.
- Identifying fields with high pollution levels.
- Sorting farms according to their annual yields.
- Calculating projected harvest production.
- Organising farm records in a structured way.
- Making the system reliable as the number of farm records increases.

The project aimed to develop Python solutions that could handle these challenges more efficiently and consistently.

# 2. Tasks and Objectives

The main objectives of the short course were to:

- Understand how different algorithms work and compare their efficiency.
- Practise searching and sorting techniques using Python.
- Apply recursion to solve sorting problems.
- Use lambda functions with `map()` and `filter()`.
- Understand Big O notation and why it matters when working with large datasets.
- Apply Object-Oriented Programming principles to real-world data.
- Create classes and objects with appropriate attributes and methods.
- Validate data and calculate crop yields and projected revenue.
- Build a field registry to manage agricultural records.

# 3. What I Learned and Deliverables

# Notebook 1: Auditing the Farm Survey

I learned how to work with searching and sorting algorithms and how to choose an appropriate approach depending on the size and structure of the data.

The main tasks included:

- Linear search to find a field using its ID.
- Binary search to find records in sorted data.
- Recursive merge sort to arrange fields according to annual yield.
- Using lambda functions and `filter()` to identify fields with pollution levels above a given threshold.
- Using lambda functions and `map()` to calculate projected harvests.
- Understanding the time complexity of algorithms through Big O notation.

**Deliverable:** Python functions for searching, sorting, filtering, and calculating projected harvests.

# Notebook 2: Modeling the Field Registry

I learned how to use Object-Oriented Programming to organise farm survey data instead of depending only on dictionaries.

The main tasks included:

- Creating a `Field` class with attributes and methods.
- Using encapsulation to validate pollution levels.
- Applying inheritance through `TeaField`, `CoffeeField`, and `WheatField` subclasses.
- Using polymorphism to work with different crop types through shared methods.
- Applying abstraction through an abstract base class.
- Creating a factory function called `build_field()`.
- Developing a `FieldRegistry` class to calculate overall projected yield and revenue.


# 4. Key Insights and Results

Through these exercises, I understood that writing code is not only about getting the correct answer. It is also important to consider efficiency, organisation, reusability, and how the system will perform as the data grows.

Some important insights were:

- Linear search checks records one by one, while binary search reduces the search space by half each time.
- Binary search requires sorted data.
- Merge sort uses recursion to divide a problem into smaller parts before combining the results.
- `filter()` selects records, while `map()` transforms records.
- Classes help organise data and the operations performed on that data.
- Inheritance allows specialised classes to reuse functionality from a parent class.
- Data validation helps prevent incorrect values from entering a system.

**Results specified in the Field Registry notebook:**

| Measurement | Expected result |

| Total farm survey records | 5,654 |
| Priced fields registered | 2,840 |
| Total projected yield | 6,103.59 |
| Total projected revenue | 6,412,228.00 |

These figures are the expected results provided by the notebook and should be confirmed by running the complete notebooks.

# 5. Technical Choices and Their Benefits

| Technology / Concept | Why it was used | Benefit |

| Python | Main programming language | Readable and suitable for data processing |
| SQLite | Accessing the farm survey database | Provides structured access to stored records |
| Linear search | Finding records in an unsorted list | Simple to implement |
| Binary search | Searching sorted records | Reduces the number of comparisons |
| Merge sort | Sorting annual yields | Efficient for larger datasets |
| Recursion | Dividing sorting problems | Makes merge sort easier to structure |
| Lambda functions | Defining short operations | Keeps filtering and mapping concise |
| Object-Oriented Programming | Modelling farm records | Improves organisation and reusability |
| Abstract classes and inheritance | Defining shared and specialised behaviour | Makes the system easier to extend |

# 6. Limitations

Although the exercises introduced useful techniques, there are some limitations:

- Binary search only works correctly when the records are sorted by the search key.
- Linear search becomes less efficient as the number of records increases.
- The crop pricing model only covers tea, coffee, and wheat.
- Projected yield and revenue depend on the values and assumptions provided in the dataset.


# 7. Next Steps

My next steps are to:

1. Improve my understanding of algorithm efficiency and advanced Python concepts.
2. Explore how these techniques can be applied to larger real-world datasets.
3. Continue developing my Python and data science skills through practical projects.

# Conclusion

This short course gave me practical experience in using Python to solve problems involving data searching, sorting, filtering, calculations, and object-oriented design.

One of my biggest takeaways was understanding that good programming is not just about making code work. It is also about making it efficient, organised, reusable, and easier for other developers to understand.

I consider this project an important step in developing my programming and data science skills.
