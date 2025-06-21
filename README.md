# Page Replacement Simulator
A Java-based simulator for visualizing and comparing different page replacement algorithms used in memory management. This project is designed to help students and enthusiasts understand how operating systems manage virtual memory through various strategies.

🚀 Features
Simulates the following page replacement algorithms:

First-In First-Out (FIFO)

Least Recently Used (LRU)

Optimal (OPT)

Clock (Second Chance)

Clock with Dirty Bit

Clock with N-Chances

Interactive command-line interface

Customizable:

Number of physical memory frames

Reference string (sequence of page requests)

🖥️ Algorithms Explained
FIFO: Replaces the oldest loaded page.

LRU: Replaces the page that was least recently accessed.

OPT: Replaces the page that won't be used for the longest time in the future.

Clock (Second Chance): FIFO + reference bit; gives pages a second chance.

Clock Dirty Bit: Prioritizes replacing clean pages (not recently written).

Clock N-Chances: Pages get multiple chances before replacement, controlled by a user-defined counter.

🛠️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/page-replacement-simulator.git
cd page-replacement-simulator
Compile the program:

bash
Copy
Edit
javac Clock.java Memory.java
Run the simulator:

bash
Copy
Edit
java Clock
📂 File Structure
Clock.java — Main class that contains all the algorithm logic and the CLI interface.

Memory.java — Helper class to simulate frame management.

🧠 Educational Use
This simulator is ideal for:

Operating Systems coursework

Algorithm comparisons

Demoing memory management concepts
