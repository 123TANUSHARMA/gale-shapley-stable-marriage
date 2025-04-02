# Gale-Shapley Stable Marriage Algorithm  

## 📌 Introduction  
This project implements the **Gale-Shapley algorithm** (also known as the **Stable Marriage Problem**) to find a stable matching between two sets of participants.  

## 🚀 Features  
- Implements the Gale-Shapley algorithm in **C++**  
- Provides an efficient solution for the **Stable Matching problem**  
- Simple and easy-to-understand code  

## 🛠 Installation & Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/123TANUSHARMA/gale-shapley-stable-marriage.git
   cd gale-shapley-stable-marriage
   ```
2. Compile the program:  
   ```bash
   g++ -o stable_matching main.cpp algorithm1.cpp poly.cpp
   ```
3. Run the executable:  
   ```bash
   ./stable_matching
   ```

## 📜 Usage  
- Modify the input preferences inside the **main.cpp** file if needed.  
- Run the program to get the stable matching output.  

## 📝 Algorithm Explanation  
The **Gale-Shapley algorithm** works as follows:  
1. Each participant in one group proposes to their most preferred choice.  
2. The receiving group tentatively accepts the best offer while rejecting others.  
3. The process continues until every participant is matched **without instability**.  

## 📖 References  
- [Gale-Shapley Algorithm - Wikipedia](https://en.wikipedia.org/wiki/Stable_marriage_problem)  

## 👩‍💻 Author  
**Tanu Sharma**  
