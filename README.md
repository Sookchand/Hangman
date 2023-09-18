
#  Hangman {Python Game}
Here's a brief description of its functionality:

1. **Setup**: The code begins by importing necessary modules and data from `hangman_words.py` and `hangman_art.py`. It then selects a random word from the word list for the game and sets up the initial game state.

2. **Game Start**: The game starts by printing the Hangman logo and the blanks for the chosen word.

3. **Guessing Letters**: The main game loop starts, where it asks the player to guess a letter. If the player guesses a letter they've already guessed, it informs them and asks for another guess.

4. **Checking Guesses**: For each new guess, it checks if the guessed letter is in the chosen word. If it is, it reveals that letter in all its positions in the word. If not, it informs the player that the letter is not in the word and reduces their remaining lives by one.

5. **End Conditions**: The game ends when either all letters in the word have been guessed (player wins), or when the player has no lives left (player loses). At each stage of the game, it prints out a visual representation of the Hangman based on how many lives are left.

This code provides a complete implementation of a console-based Hangman game.
#  Acknowledgements
I would like to thank Dr. Angela Yu.
## Authors

- [@Sookchand](https://github.com/Sookchand)


## Screenshots

![hangman](https://github.com/Sookchand/Hangman/assets/34344439/20ddb0d1-ecad-44d6-9d3c-36de46a07495)



## Tech Stack
The specific “tech stack” for this game includes:

Python: The core language used to implement the game logic.
Python Standard Library: Used for functionalities like random choice (random.choice), user input (input()), and string manipulation.
Google Colab: It seems you’re running this code in Google Colab, which is a cloud-based Python notebook service.
The game also relies on two custom Python modules:

hangman_words.py: This module contains the list of words that the game can choose from.
hangman_art.py: This module contains ASCII art for the hangman stages and the game logo.
These modules are part of your project’s codebase and aren’t part of any larger framework or library. These are specific to my game.
## Documentation
Here are some resources that you might find helpful:

**Python Documentation and Tutorials:**
- [Real Python's Guide to Documenting Python Code](^1^)
- [Python's Official Website](^2^)
- [W3Schools Python Tutorial](^8^)
- [Python 3.11.5 Documentation](^9^)
- [TutorialsPoint Python Tutorial](^10^)

**Google Colab Documentation and Tutorials:**
- [Google Colab's Official Introduction](^4^)
- [Google Colab's Basic Features Overview](^5^)
- [TutorialsPoint Google Colab Tutorial](^12^)

These resources cover a wide range of topics from basic to advanced concepts in Python and Google Colab. They should help you get started or deepen your understanding of these tools. Happy learning! 😊

Source: Conversation with Bing, 9/18/2023
(1) Documenting Python Code: A Complete Guide – Real Python. https://realpython.com/documenting-python-code/.
(2) Welcome to Python.org. https://www.python.org/?country=209.
(3) Python Tutorial - W3Schools. https://www.w3schools.com/python/.
(4) The Python Tutorial — Python 3.11.5 documentation. https://docs.python.org/3/tutorial/index.html.
(5) Python Tutorial - Online Courses and eBooks Library. https://www.tutorialspoint.com/python/index.htm.
(6) Google Colab. https://colab.research.google.com/.
(7) Google Colab. https://colab.research.google.com/notebooks/basic_features_overview.ipynb.
(8) Google Colab Tutorial - Online Tutorials Library. https://www.tutorialspoint.com/google_colab/index.htm.
(9) Python. https://docs.python.org/2.7/.
(10) Google Colab. https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/01.01-Help-And-Documentation.ipynb.
(11) Google Colab. https://colab.research.google.com/notebooks/io.ipynb.
(12) Google Colab. https://colab.research.google.com/notebooks/intro.ipynb.
(13) Google Colab Tutorial. https://colab.research.google.com/github/ga642381/ML2021-Spring/blob/main/Colab/Google_Colab_Tutorial.ipynb.
(14) undefined. https://python.org.
(15) undefined. https://www.python.org/.
## Lessons Learned
Building a game like Hangman in Python can teach you several important programming concepts and skills:

1. **Control Structures**: The game loop uses a `while` loop to keep the game running until the player wins or loses. Inside this loop, `if` statements are used to check the player's guesses and update the game state.

2. **Data Structures**: Lists are used to store the letters of the chosen word and the player's current guesses. This teaches you how to work with one of Python's basic data structures.

3. **Functions and Modules**: The code uses functions from the `random` module in the Python Standard Library, as well as custom modules (`hangman_words` and `hangman_art`). This can help you understand how to use and create your own modules and functions.

4. **Input/Output**: The game takes input from the player using Python's `input()` function, and prints output using the `print()` function. This can help you understand how to interact with users in a console application.

5. **Error Handling**: The code includes checks to handle situations like the player guessing a letter they've already guessed. This can introduce you to the concept of error checking and handling in your code.

6. **Problem Solving**: Implementing a game like Hangman requires problem-solving skills to figure out how to translate the rules of the game into code.

7. **Code Organization**: The use of TODO comments in the code can teach you about organizing and planning your code, making it easier to read and maintain.


# Hi, I'm Sookchand! 👋

Strive to improve with each passing moment, surpassing the person I was in the previous minute, the previous hour, and even the person you were yesterday.
## 🚀 About Me
I have experience as a data scientist and machine learning engineer. I have worked on projects involving the development of predictive models, the optimization of machine learning algorithms, and the deployment of machine learning models. I have also worked on projects involving the analysis of large datasets, the development of data-driven insights, and the creation of data visualizations.
## 🛠 Skills
I possess a wide range of skills including:

- **Data Analysis**: Proficient in Data Exploration and Visualization, Model Evaluation and Analysis, and Regression Analysis.
- **Machine Learning**: Experienced in Neural Network and Deep Learning, Supervised Learning (including Classification, Regression, and Time Series), Decision Trees and Random Forests, Ensemble Learning, and Hyperparameter Tuning.
- **Libraries and Frameworks**: Skilled in using TensorFlow 2.0, NumPy, Scikit Learn, Keras, Pandas, React.js, Node.js, Express.js with Node.js.
- **Big Data Technologies**: Familiar with Hadoop, Apache Spark, Kafka, and Apache Flink.
- **Image Processing**: Capable of performing Image Recognition and Classification, and Transfer Learning.
- **Programming Languages**: Proficient in Python and R. Also have experience with HTML, CSS, JavaScript ES6, DOM, JQuery.
- **Database Management**: Knowledgeable in SQL and MongoDB along with Mongoose.
- **Web Development**: Experienced in HTML, CSS, Bootstrap 4, JavaScript ES6, DOM, JQuery.
- **Version Control Systems**: Comfortable with Git, GitHub.
- **Data Visualization Tools**: Proficient in Tableau and Power BI.
- **Authentication and Security**: Familiar with various authentication and security protocols.
- **Other Skills**: Comfortable working with GPU on Google Collab. Familiar with Unix Command-Line.

This diverse skill set allows me to tackle a variety of data science and web development projects.
