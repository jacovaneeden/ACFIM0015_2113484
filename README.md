# ACFIM0015_2113484
ACFIM0015 Algorithmic Trading Coursework

The GRU works by running the individual code cells in GRU.ipynb. It uses the 'tape_saved.csv' file, and tests on the 'test_tape.csv' file.

The model parameters are saved to gru_model.pt, and the scalar is saved to scaler.pt.

Check that no path errors in BSE.py are present, then everything should work. Note that my PT2 trader needs to import the gru_model.pt and scaler.pt files to work. Their locations are currently written as relative paths, but if these files are moved around out of different directories, then the file paths will need to be changed. So basically, keep everything in the same directory.

BSE.py has my adjusted PT2 trader in it. 

Notes:
Important library required: torch (used by GRU)
Install in terminal with: pip install torch

BSE References:
https://github.com/davecliff/BristolStockExchange
Cliff, D. (2018). BSE: A Minimal Simulation of a Limit-Order-Book Stock Exchange. In M. Affenzeller, et al. (Eds.), Proceedings 30th European Modeling and Simulation Symposium (EMSS 2018), pp. 194-203. DIME University of Genoa.
