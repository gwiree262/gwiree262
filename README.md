import matplotlib.pyplot as plt 
from matplotlib import pylab
import seaborn as sns
pylab.rcParams['figure.figsize'] = (3, 3)

sns.set(style="white")
sns.set(style="whitegrid", color_codes=True)
df = pd.read_csv("https://raw.githubusercontent.com/madmashup/targeted-marketing-predictive-engine/master/banking.csv")
ncol = df.shape[1]
pd.set_option('display.max_columns', ncol)
