📌 ***Project Overview***

Trip Planner is a C++ application designed to help users plan optimal travel routes and activities based on their budget, time constraints, and preferences.
The system leverages graph algorithms (TSP with backtracking), greedy optimization, and file handling to generate efficient itineraries.


✨ ***Key Features***

✅ *Optimal Route Planning*

Solves the Traveling Salesman Problem (TSP) using backtracking to minimize travel distance/cost. Supports road, train, and flight transport modes with real-time cost/duration comparisons.

✅ *Activity Scheduling*

Greedy algorithm selects activities within budget/time limits. Haversine formula calculates distances between geographic coordinates.

✅ *User-Friendly Interface*

Interactive console menus for inputting cities, budgets, and transport preferences. Detailed itinerary tables with segment-wise breakdowns (distance, cost, time).

✅ *Data-Driven*

CSV files store city/activity data for dynamic updates.


🛠️ ***Technologies Used***

**Language: C++**

**Algorithms:**

->Linear Search in Vector

->Graph Construction

->Backtracking (TSP)

->Greedy (Activity selection)

->Sorting (Priority-based optimization)

**Data Structures:**

->1D/2D Arrays(City Info)

->Graphs (Adjacency lists for cities/activities)

->Hash maps (Fast lookups)

->Recursion Stack (TSP path exploration)

**Tools:**

->File I/O (CSV parsing)
->Haversine formula (Distance calculations)


***📝 Key Functions***

*Function*	           *Purpose*
tspBacktrack()	       Recursive TSP solver

loadDataFromCSV()	     Parses city/activity data

getOptimalActivities() Greedy activity selector

calculateDistance()	   Haversine formula impl.


***🚀 How to Run***


**Prerequisites**
*C++ Compiler*: Install g++ (GNU C++ Compiler)

->Linux: sudo apt install g++ (Debian/Ubuntu)

->Mac: Install Xcode Command Line Tools: xcode-select --install

->Windows: Install MinGW or use WSL

*Git (optional, for cloning)*: sudo apt install git

