Major Areas: 
Equations, Graphs, and Functions
Derivatives and Optimization
Vectors and Matrices
Statistics and Probability


Ref:
Plot area filled under the curve - 
# show area for integral
section = np.arange(0, 2, 1/30) #step value is key - we can give any small step
plt.fill_between(section,f(section), color='orange') #in this case f(section) = section
Quiver Plot and Scipy limits - to indicate vector directions in plot
magnitude using - np.linalg.norm(v)
degree theta - math.atan(vTan)
Different types of vector multiplication
Matrices - np.array and np.matrix, properties, np.linalg.inv
Eigen Values and Eigen Vectors - eVals, eVecs = np.linalg.eig(A)
Eigen Decomposition - A = QλQ-1
Different types of charts - Bar, Pie, Line, Density Plots
Lines on Histograms to indicate Mean, Median, Mode - linestyle, linewidth
Percentile - scipy.stats.percentileofscore() - Weak and Strong percentiles
Data Comparison - Impact of Normalization
Conditional Probability
Binomial Theorem
Confidence Interval - ci = stats.norm.interval(0.95, m, sd)
One Tailed, Two Tailed Hypothesis Testing

random.randint(1,5) - Generate random integer between a and b
random.randint(1,5,5) - Generate 5 random integer between a and b
np.array(values/range) - Generate Numpy array
y = [f(i) for i in x] - dependent list Y using comprehension
el = np.arange(-5,6) - Generating an array of numbers in range
nx, ny = np.meshgrid(el, el, sparse=False, indexing='ij') - create a mesh grid - Matrix arrangement of axa
np.random.normal(mu, sigma, n) - Create a normal distribution
