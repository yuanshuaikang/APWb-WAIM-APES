# APWb-WAIM-APES

**APES (Adaptive Pattern Exploration System)** is an interactive system for discovering high-utility spatial patterns. Designed with a user-centric approach, APES integrates user feedback into the mining loop to guide the search toward patterns that satisfy both predefined constraints and user interests.

The system is developed using **PyQt5** for the graphical user interface and supports real-time interaction, pattern visualization, and feedback-driven refinement.

## Features

- Adaptive mining of spatial high-utility patterns  
- Probabilistic modeling and iterative sampling  
- Interactive user feedback integration  
- Real-time visualization of mining progress  
- Support for custom spatial and utility data inputs  
- Built with PyQt5 for an intuitive desktop UI  

## Installation

1. Clone this repository:

```bash
git clone https://github.com/yuanshuaikang/APWb-WAIM-APES.git
cd APWb-WAIM-APES
````

2. (Optional) Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

> Or manually install:

```bash
pip install PyQt5 numpy pandas
```

## Usage

Run the main application file:

```bash
python main_program.py
```

Once launched:

1. Import spatial and utility data files (CSV format)
2. Set mining parameters via the control panel
3. Interactively select target features and review discovered patterns
4. Provide feedback on selected patterns to refine future iterations

## File Structure

```
APWb-WAIM-APES/
├── main_program.py        # Entry point
├── data/                  # Example datasets
├── README.md
```

## Dependencies

* Python 3.7+
* PyQt5
* numpy
* pandas

