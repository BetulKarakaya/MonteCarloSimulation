# 🎲 Monte Carlo Simulations Playground 🎲  

Welcome to the **Monte Carlo Simulations** repository! 🚀 This repo is a collection of Python-based simulations that use the **Monte Carlo method** to estimate probabilities, model real-world scenarios, and analyze randomness. Whether you're a **data scientist, mathematician, or just a curious coder**, this is the perfect place to explore the power of probabilistic simulations.  

---

## 📌 What is Monte Carlo Simulation?  
Monte Carlo simulations rely on **random sampling and statistical modeling** to estimate numerical results that may be difficult (or impossible) to compute analytically. They are widely used in **finance, physics, engineering, AI, and probability theory** to solve problems with uncertainty and randomness.  

### ✅ Key Features of Monte Carlo Simulations:  
✔️ **Random Sampling:** Uses large numbers of random trials  
✔️ **Statistical Approximation:** Estimates probabilities when exact solutions are complex  
✔️ **Real-World Applications:** Used in decision-making, risk analysis, and scientific modeling  

---

## 🚀 Included Simulations  

### 🎲 1. Dice Roll Probability Simulation
**Goal:** Estimate the probability of rolling a specific sum (e.g., 8) when rolling two six-sided dice.

**How It Works:**
- Simulates 100,000 dice rolls.
- Counts occurrences where the dice sum equals the target.
- Computes the probability and compares it to the theoretical value.
- Visualizes the results with a pie chart. 🥧

### 🪙 2. Coin Toss Probability Simulation
**Goal:** Estimate the probability of getting heads or tails in a large number of coin flips.

**How It Works:**
- Simulates 100,000 coin flips using Monte Carlo methods.
- Calculates the frequency of heads and tails.
- Computes the probability of heads and tails.
- Visualizes the results with:
  - 🥧A pie chart showing the probability distribution of heads and tails.
  - 📊A bar chart displaying the total occurrences of heads and tails.
- Demonstrates the Law of Large Numbers, as the probability should converge to 50% for each outcome when the sample size is large enough.

### 🪙 3. Three Coin Toss Probability Simulation
**Goal:** Estimate the probability of getting at least one 'Tails' when flipping three fair coins.

**How It Works:**
- Simulates 100,000 trials where three coins are flipped per trial.
- Determines how many trials contain at least one 'Tails'.
- Computes the estimated probability and compares it to the theoretical probability:

  \[
  P(At least one Tails) = 1 - P(No Tails)
  \]

  \[
  = 1 - (1/2 × 1/2 × 1/2) = 1 - 1/8 = 7/8 ≈ 0.875
  \]

- Visualizes the results with:
  - 📊 A bar chart showing the frequency of 'Heads' and 'Tails' across the three coin flips.
  - 🥧A pie chart illustrating the probability distribution of getting at least one 'Tails'.


 ### 🎲 4. Dice Face Probability Simulation
**Goal:** Estimate the probability distribution of each face (1-6) in a large number of dice rolls.

**How It Works:**
- Simulates 100,000 dice rolls using Monte Carlo methods.
- Counts how many times each face (1-6) appears.
- Computes the experimental probability for each face.
- Compares experimental probabilities with the theoretical probability (1/6 ≈ 16.67%).
- Visualization:
   - 📊 Bar Chart: Displays how frequently each face appeared.
   - 🥧 Pie Chart: Shows the probability distribution of each die face.
- 🔢 Demonstrates the Law of Large Numbers, where probabilities should approach 1/6 as the number of trials increases.
This simulation helps understand randomness and probability distribution in rolling a fair die! 🎲✨


### 🎱 5. Monte Carlo Ball Selection Simulation  
**Goal:** Estimate the probability of drawing a specific colored ball from a bag containing multiple colors.  

#### **How It Works:**  
- The user defines the number of **balls for each color** in a bag.  
- A **random ball** is drawn from the bag for a large number of trials (e.g., 100,000).  
- Counts how many times the **target color** is drawn.  
- Computes the experimental probability and compares it with the theoretical probability.  

#### **Visualization:**  
📊 **Bar Chart:** Displays the frequency of each color drawn.  
🥧 **Pie Chart:** Illustrates the probability distribution of the selected ball colors.  

#### **Concepts Demonstrated:**  
🔹 **Law of Large Numbers:** As the number of trials increases, the observed probability should approach the theoretical probability.  
🔹 **Random Sampling:** Simulating real-world probability experiments through random selections.  
🔹 **Monte Carlo Simulation:** Using repeated random sampling to estimate the likelihood of an event.  

This experiment helps understand probability theory in random selection scenarios, like **lotteries, game mechanics, and real-world decision-making processes!** 🎯✨  

### 🔢 6. Monte Carlo Simulation: Estimating the Probability of Numbers in a Given Range
**Goal:** Estimate the probability of a randomly selected number falling within a specified range using the Monte Carlo method.

#### How It Works:
- The user defines a number space [min, max) and a search range within this space [min, max).
- A large number (default: 100,000) of random numbers are generated from the space.
- The program calculates how many numbers fall within the search range.
- The probability is computed as the proportion of numbers falling within the specified range.
- Results are displayed as both numerical output and visualized using bar and pie charts.

#### Visualization:
- **Bar Chart:** Displays the distribution of numbers inside and outside the specified range.
- **Pie Chart:** Illustrates the probability of a number appearing within the specified range.
This simulation demonstrates random sampling and probability estimation. It provides insights into understanding randomness and probability theory, which can be applied in fields like data science, statistics, and decision-making.📈📚

 ### 🔢 7. Monte Carlo Simulation: Estimating the Probability of Even Numbers in a Given Range  

**Goal**:  
Estimate the probability of randomly selecting an even number from a user-defined range using the Monte Carlo method.  

#### How It Works:  
- The user defines a number space \([ \text{min}, \text{max} )\).  
- A large number (default: 100,000) of random integers are generated within this space.  
- The program calculates how many of these numbers are even.  
- The probability is computed as:  
- **P(even) = Number of even numbers / Total generated numbers**
- Results are displayed both numerically and visually using charts.  

#### **Visualization: ** 
- 📊 **Bar Chart**: Displays the distribution of even and odd numbers.  
- 🥧 **Pie Chart**: Illustrates the probability of selecting an even number.  

This simulation demonstrates random sampling and probability estimation. It provides insights into understanding randomness and probability theory, applicable in fields like data science, statistics, and decision-making. 📈📚  


