# Star - Quest
 The StarMap application oÐers an immersive platform for stargazing enthusiasts to ex
plore the night sky, engage in educational quizzes, manage user proÑles, and interact
 with celestial objects. This Java-based application integrates with a MySQL database to
 provide dynamic content and personalized user experiences.
 # Features and Functionality
 # IntroPage3 Class
 The IntroPage3 class serves as the entry point to the application, presenting a JFrame
 with an animated background panel featuring moving stars.
 1. Login Functionality: Existing users can authenticate themselves by entering their
 username and password. The application veriÑes these credentials against the user
 table in the MySQL database.
 2. Account Creation: New users can register by providing their name, desired user
name, password, and location. Upon successful account creation, the information
 is stored securely in the user table for future logins.
 3. Dynamic Background: The animated starry background creates an immersive
 atmosphere for users interacting with the application.
 # QuizPage Class
 The QuizPage class hosts interactive quizzes by fetching random questions from a MySQL
 database (stars500) and updating user scores based on their answers.
 1. Each login displays a randomly selected question fetched from the quiz table in the
 database.
 2. Users select an option, and their answer is evaluated against the correct answer
 stored in the database.
 3. Scores are dynamically updated based on correct answers, allowing users to track
 their progress and knowledge of astronomy.
# DatFile Class
 The DatFile class fetches star data from a MySQL database (stars500) and processes
 it to create a 2D array representing the night sky.
 1. Connects to a MySQL database to retrieve detailed information about stars, in
cluding their celestial coordinates, magnitude, and spectral classiÑcation.
 2. Converts celestial coordinates to screen coordinates for rendering, allowing users to
 visualize star positions accurately on the virtual sky map.
 3. Adjusts star magnitude based on spectral index and visibility, enhancing the realism
 and beauty of the starry night simulation.
 # UserPage Class
 The UserPage class displays user statistics, including leaderboards, favorites, and achieve
ments, fetched from a MySQL database (stars500).
 1. Leaderboard Display: Shows usernames and scores in descending order, allowing
 users to compare their performance with others.
 2. Favorites List: Showcases stars favorited by the user, providing quick access to
 preferred celestial objects for further exploration.
 3. Achievements Tracker: Lists earned badges and accomplishments based on user
 interactions and quiz performance.
 # StarMap Class
 The StarMap class initializes the main application window, incorporating interactive fea
tures, dynamic animations, and user interface components.
 1. Animated Background: Features a dynamic background with moving stars to create
 an immersive stargazing experience.
 2. Rocket Animation: Enhances visual appeal by incorporating animated elements
 like a rocket moving across the screen, adding to the cosmic ambiance.
 3. Customizable ProÑles: Allows users to upload a proÑle picture and view their unique
 username and user ID, fostering a personalized and engaging user experience.
 # Usage
 1. Main Menu: Launch the StarMap application to access the main menu.
 2. Login or Create Account: Use existing credentials to log in or register as a new
 user to unlock the application's features.
 3. Explore the Night Sky: Interact with the night sky by participating in quizzes,
 viewing user proÑles, and exploring celestial objects.
 4. Track Progress: Monitor quiz scores, achievements, and favorites to enhance
 knowledge and engagement with astronomy topics.
 5. Customize ProÑles: Personalize user proÑles with proÑle pictures and unique
 settings to make the experience more immersive.
 # Dependencies
 1. Java SE Development Kit (JDK)
 2. MySQL Connector/J for database connectivity
 3. Java Swing for GUI components
 # File Structure
 1. IntroPage3.java: Manages user authentication and account creation functionali
ties.
 2. QuizPage.java: Hosts interactive quizzes and updates user scores based on quiz
 performance.
 3. DatFile.java: Retrieves and processes star data from the MySQL database for
 rendering the night sky.
 4. UserPage.java: Displays user statistics and proÑles, including leaderboards, fa
vorites, and achievements.
 5. StarMap.java: Initializes the main application window and incorporates interactive
 features for stargazing exploration.
 # Conclusion
 The StarMap application combines educational content with interactive features to of
fer users a captivating journey through the cosmos. By leveraging Java programming
 and MySQL database integration, StarMap provides an engaging platform for stargazing
 enthusiasts, learners, and curious minds alike.
