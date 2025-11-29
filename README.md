# Course315_MLOpt

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
from scipy.optimize import minimize, differential_evolution
from sklearn.tree import DecisionTreeRegressor, export_text
from pandas.plotting import parallel_coordinates

# --- CORE PHYSICS ENGINE (Your Corrected Utility) ---
def get_R(x, k_q=0.99, c=2.5):
    q = np.clip(k_q * (2 * x + e), 0.001, 0.999)
    return (swe)
