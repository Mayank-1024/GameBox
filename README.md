# GameBox

A Cognitive Game Suite for Alzheimer Patients | INFO6205 PSA Final Project

---

## 🌐 Project Mission

**GameBox** is a modular suite of JavaFX mini-games aimed to support memory training and cognitive reinforcement for Alzheimer patients. Inspired by game-based learning techniques, our project integrates Data Structures & Algorithms into user-friendly, accessible interactive experiences.

---

## 🔬 Key Features

- **Flashcard Memory Game** - Randomized visual flashcards, Stack logic.
- **Reaction Timer Game** - Measures reflexes, PriorityQueue for top scores.
- **Memory Recall Game** - Emoji recall with Set<String> and List<String>.
- **Path Finder Game** - Grid traversal using BFS and Queue.
- **Card Match Game** - Pair matching using HashMap<Button, String>.
- **Binary Search Tree Game** - BST navigation with recursion and Stack.


---

## 🧵 Data Structures & Algorithms Used

| Game                | Data Structure / Algorithm           |
|---------------------|--------------------------------------|
| Flashcard           | Custom Stack (LinkedList)            |
| Reaction Timer      | PriorityQueue<Long>                  |
| Memory Recall       | Set<String>, List<String>            |
| Path Finder         | Queue<Node>, Graph Traversal (BFS)   |
| Card Match          | HashMap<Button, String>              |
| Binary Search Tree  | Recursive BST, Stack for backtracking|


---

## 🔧 Tools & Technologies

- **Java Version:** Java 21 (or higher)
- **UI Framework:** JavaFX SDK 21
- **IDE:** Eclipse IDE for Enterprise Java and Web Developers
- **Build System:** Manual javac, Eclipse classpath setup
- **Architecture:** MVC (Model-View-Controller)


---

## 📈 Project Discussion

**What Went Well:**
- Modular design with separate controllers per game
- Clean integration of Data Structures into UI logic
- Smooth collaboration using Git and Eclipse

**Challenges:**
- Handling JavaFX threading for animations and timers
- Integrating academic DSA concepts into real-world UI flows

**Learning Outcomes:**
- Reinforced algorithmic thinking through gamification
- Mastered JavaFX event-driven programming and FXML handling
- Gained deep understanding of managing UI/logic separation


---

## 📚 How to Setup GameBox in Eclipse

### 1. Install JDK
- Download and install JDK 21 or higher:  
  [Download Java JDK](https://jdk.java.net/21/)

### 2. Install JavaFX SDK
- Download JavaFX SDK matching your JDK version:  
  [Download JavaFX SDK](https://gluonhq.com/products/javafx/)


### 3. Clone Project
```bash
# Clone GameBox Repository
$ git clone https://github.com/Mayank-1024/GameBox.git
```


### 4. Import Project in Eclipse
- Open Eclipse → `File → Import → Existing Projects into Workspace`
- Select the GameBox project folder
- Finish Import


### 5. Configure JavaFX Libraries
- Right-click on the project → `Build Path → Configure Build Path`
- Under **Libraries** tab:
  - Click **Add External JARs**
  - Add these JARs from your JavaFX `lib/` folder:
    - javafx.base.jar
    - javafx.controls.jar
    - javafx.fxml.jar
    - javafx.graphics.jar
    - javafx.media.jar
    - javafx.swing.jar
    - javafx.web.jar


### 6. Add VM Arguments
Go to:
- `Run → Run Configurations → Arguments Tab → VM Arguments`
- Add:
```bash
--module-path /path/to/javafx-sdk-21/lib --add-modules javafx.controls,javafx.fxml
```
*(Adjust path according to your system)*


### 7. Run `GameBoxApp.java`
- Right-click `GameBoxApp.java` → Run As → Java Application
- The GameBox menu should appear with options for all games!


---

## 🔗 Links
- [Download JDK 21](https://jdk.java.net/21/)
- [Download JavaFX SDK 21](https://gluonhq.com/products/javafx/)


---

> 🔗 **Built with passion for cognitive reinforcement and DSA mastery!**

> Mayank Bhadrasen

---

