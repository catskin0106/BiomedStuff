[Lecture Notes](https://cs231n.stanford.edu/slides/2025/lecture_2.pdf)

**Lecture Coverage:**
- k-Nearest Neighbor
- Linear Classification
- Cost Functions: SoftMax & Cross Entropy
- Cost Functions: Multiclass SVM Loss

---
#### **k-Nearest Neighbor**
- Predicts labels based on the k-nearest training examples on a multidimensional space
- Hyperparameters:
	- Distance Metric: The method to measure distance
		- L1 (Manhattan): Measured by Moving Along Gridlines
			- like moving in a city w/ square blocks
		- L2 (Euclidean): Measured by Straight-Line Distance
	- k: The amount of neighbors to reference

**Evaluation of Hyperparameters**
- Separate training data into training set & validation set
	- Use the validation set to calibrate hyperparameters


#### **Linear Classification**
- A function that returns class scores for each <abbr Title="Objects to be identified">class</abbr> to an input
	- e.g. A dog image will desirably have higher dog class score than cat
- Through <abbr Title="e.g. Adding the values of all pixels in a picture after manipulating their values with their corresponding weights">weighted summation of input parameters</abbr> and adding bias constant
	- s = f(x,W) = Wx + b

**Evaluation of Weights**
- Define a Loss Function to calculate discrepancy between AI predication and ground truth
	- Optimize the weights so that the loss function is minimized


#### **Loss Functions**
- The discrepancy between ground truth and the AI prediction
	- Ground truth: 1 in the truth class, and 0 in every other class

**SoftMax Function: P(Y=k | X=x<sub>i</sub>)**
- Function that converts score to probabilities
	- Easier to compare to ground truth as probabilities add to 1
	- Retains relative confidences of other classes → Helps in training to improve AI confidence

$$
\Huge P(Y=k |X=x_{i})=\frac{e^{s_{k}}}{\sum_{j}^{K}e^{s_{j}}}\huge 
$$
- <abbr Title="Probability of image Y being class K happening based on training set xi">P(Y=k|X=x<sub>i</sub>)</abbr>, <abbr Title="The class score of class i for the image">s<sub>i</sub></abbr>, <abbr Title="for j=1;j<=K;j++">The Σ thing</abbr>
- Steps of Loss Calculation through SoftMaxxing:

|               Step                |                        Example (3 classes)                         |            <            |            <            |
| :-------------------------------: | :----------------------------------------------------------------: | :---------------------: | :---------------------: |
|       Original class scores       |                                3.2                                 |           5.1           |          -1.7           |
| Exponentiate all the class scores |                       e<sup>3.2</sup> = 24.5                       | e<sup>5.1</sup> = 164.0 | e<sup>-1.7</sup> = 0.18 |
|   Normalize into Probabilities    | e<sup>3.2</sup> / (e<sup>3.2</sup> + e<sup>5.1</sup> + ...) = 0.13 |         = 0.87          |         = 0.00          |
|     Compare with Ground Truth     |                            0.13 V.S. 1                             |       0.87 V.S. 0       |        0 V.S. 0         |

**Cross Entropy (L<sub>i</sub>)**
- Function to use in combination with SoftMax
	- Negative log of the probability of the truth class (p<sub>i</sub>) only
	- Punishes wrong and confident predictions much more severely → Helps in determining the gradient of nudging weights

$$
\Huge L_{i}=-\log(p_{i})
$$


|                  Case                   |                  Outcome                  |
| :-------------------------------------: | :---------------------------------------: |
| p<sub>i</sub> = 1 (Confident & Correct) |             L<sub>i</sub> = 0             |
|   p<sub>i</sub> = 0.5 (Not confident)   |         L<sub>i</sub> = about 0.7         |
|  p<sub>i</sub> = 0 (Confident & Wrong)  | L<sub>i</sub> skyrockets towards infinity |


#### **Cost Functions: Multiclass SVM Loss**
