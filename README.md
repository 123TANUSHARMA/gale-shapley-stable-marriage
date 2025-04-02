Gale-Shapley Stable Marriage Algorithm
📌 Introduction
This project implements the Gale-Shapley algorithm (also known as the Stable Marriage Problem) to find a stable matching between two sets of participants.

🚀 Features
Implements the Gale-Shapley algorithm in C++

Provides an efficient solution for the Stable Matching problem

Simple and easy-to-understand code

🛠 Installation & Setup
Clone the repository:

bash
Copy
Edit
git clone https://github.com/123TANUSHARMA/gale-shapley-stable-marriage.git
cd gale-shapley-stable-marriage
Compile the program:

bash
Copy
Edit
g++ -o stable_matching main.cpp algorithm1.cpp poly.cpp
Run the executable:

bash
Copy
Edit
./stable_matching
📜 Usage
Modify the input preferences inside the main.cpp file if needed.

Run the program to get the stable matching output.

📝 Algorithm Explanation
The Gale-Shapley algorithm works as follows:

Each participant in one group proposes to their most preferred choice.

The receiving group tentatively accepts the best offer while rejecting others.

The process continues until every participant is matched without instability.

📖 References
Gale-Shapley Algorithm - Wikipedia

👩‍💻 Author
Tanu Sharma

