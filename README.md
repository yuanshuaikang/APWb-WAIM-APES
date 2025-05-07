# APWb-WAIM-APES

**APES (Adaptive Pattern Exploration System)** is an interactive system for discovering high-utility spatial patterns. Designed with a user-centric approach, APES integrates user feedback into the mining loop to guide the search toward patterns that satisfy both predefined constraints and user interests.

The system is developed using **PyQt5** for the graphical user interface and supports real-time interaction, pattern visualization, and feedback-driven refinement.

## Features

-  Adaptive mining of spatial high-utility patterns
-  Probabilistic modeling and iterative sampling
-  Interactive user feedback integration
-  Real-time visualization of mining progress
-  Support for custom spatial and utility data inputs
-  Built with PyQt5 for an intuitive desktop UI

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yuanshuaikang/APWb-WAIM-APES.git
cd APES

2. Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install dependencies:
pip install -r requirements.txt

pip install PyQt5 numpy pandas

# Usage
Run the main application file:

python main.py

Once launched:

1. Import spatial and utility data files (CSV format).

2. Set mining parameters via the control panel.

3. Interactively select target features and review discovered patterns.

4. Provide feedback on selected patterns to refine future iterations.

# File Structure
APES/
├── main.py                # Entry point
├── data/                  # Example datasets
├── README.md








