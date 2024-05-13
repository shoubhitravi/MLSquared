# MLSquared

Welcome to MLSquared, a comprehensive learning platform geared towards data scientists of all levels, from beginners to those already in the field. MLSquared is a high-quality, user-friendly, and free application with the goal of increasing educational equity by making it accessible for anyone with an internet connection to learn about data analysis and machine learning. We especially made our platform easy to understand and simple to navigate, demystifying the process of modeling data for anyone who has ever wanted to try.  

MLSquared offers three interesting datasets, a training module that encourages users to get creative with their models, and a leaderboard that tracks and compares model performance, and allows users to leave thoughts in comments on the entries. 

## Project Structure

Below is an overview of the key directories and files within the ML Squared project repository:

/326_EDUCATION_APP
│
├── Data                     # Contains various datasets
│
├── node_modules             # Node.js packages (not tracked by Git)
│
├── src                      # Source files for the application
│   ├── client               # Client-side code
│   │   ├── db.js            # Database interaction scripts
│   │   ├── github.txt       # GitHub configuration (likely should be .gitignored)
│   │   ├── index.html       # Main HTML document
│   │   ├── script.js        # Client-side JavaScript
│   │   └── styles.css       # Stylesheet for the application
│   │
│   ├── server               # Server-side code
│   │   ├── data             # Data files for server use
│   │   │   ├── boston.csv   # Dataset for Boston housing
│   │   │   ├── housing_mod.csv  # Modified housing dataset
│   │   │   ├── housing.csv  # Original housing dataset
│   │   │   ├── titanic.csv  # Dataset for Titanic passengers
│   │   │   └── WineQT.csv   # Wine quality dataset
│   │   │
│   │   ├── models          # Machine learning models
│   │   │   ├── decision.py  # Decision tree model
│   │   │   ├── lin_reg.py   # Linear regression model
│   │   │   ├── nn.py        # Neural network model
│   │   │   └── testNN.py    # Test script for neural networks
│   │   │
│   │   ├── backend.js      # Backend utility functions
│   │   └── server.js       # Node.js server setup
│   │
│   └── training.js         # Script for training models
│
├── docs                     # Documentation files
│   └── milestone-01         # Documentation for milestone 1
│
├── .gitignore               # Specifies intentionally untracked files to ignore
├── package.json             # NPM package and dependency definitions
├── package-lock.json        # Locked versions of the package dependencies
└── README.md                # Project documentation
