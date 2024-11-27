# Crime Investigation Game - DBMS Mini Project

## Project Title:
**CRIME INVESTIGATION GAME**

## Problem Statement:
A Crime Investigation Game where players solve puzzles to uncover the identity of the criminal among multiple suspects. Each puzzle provides clues that describe the actual criminal, requiring players to use their deduction and problem-solving skills to crack the case. The game offers an engaging blend of storytelling and interactive challenges for an immersive experience.

## Brief Software Requirements Specifications (SRS):

### 1. Purpose:
The primary purpose of this SQL code is to structure and populate a database for crime cases. Each case has multiple suspects, clues, and hints that players can analyze to solve mysteries. The database is designed to help players uncover the culprit by examining the relationships and information stored in each case.

### 2. Key Features:
- **Case Structure:** Each case in the game has a unique ID, title, and overview that provides a brief description of the mystery, setting up the scenario for players.
- **Puzzles and Clues:** The puzzle table includes clues and questions related to each case, guiding players in investigating and uncovering answers relevant to solving the crime.
- **Hints:** The hint table offers additional guidance for each puzzle, helping players when they are stuck or need more context to interpret clues.
- **Suspects:** The suspect table lists individuals associated with each case, including their background and potential motives. The "culprit" attribute (boolean) indicates if a suspect is guilty, which players aim to deduce.
- **Culprit Identification:** Each case includes at least one suspect with a culprit flag set to true, marking them as the guilty party, allowing the game logic to verify if the player’s deductions are correct.

### 3. Non-Functional Requirements:
- **Performance:** The database should be optimized to handle multiple simultaneous queries since players will likely check clues, suspects, and hints frequently.
- **Scalability:** The database schema should support easy expansion without significant structural changes.
- **Reliability and Data Integrity:** Constraints like foreign keys between tables should be enforced to maintain data integrity.
- **Security:** Sensitive information, such as the culprit's identity, should be protected to prevent data leaks.
- **User-Friendly Query Structure:** Queries should be optimized for readability and efficiency.

### 4. Normalization up to 3NF:
