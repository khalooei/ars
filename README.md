# Adversarial Robustess Stack
A descriptive anchor and stack for adversarial machine learning researchers


### *Linf* attacks
* MNIST dataset (Kaggle CNN model)

|       |   0.01   |   0.03   |   0.1   |   0.2   |   0.3   |
|-------|----------|----------|---------|---------|---------|
|  FGSM   |   98.44   |   96.51   |   73.56  |   23.59   |   **13.32**   |
|  PGD-50 |   **98.39**   |   **92.52**  |   8.25   |   0.24   |   0.10   |
|  FFGSM  |   98.42 |   96.42  |  **84.28**  |   **38.74**   |   12.03   |

* CIFAR10 dataset (WRN-28 model)

|       |   0.01   |   0.03   |   0.1   |   0.2   |   0.3   |
|-------|----------|----------|---------|---------|---------|
|  FGSM   |  24.03  |   11.44   |   10.59  |      |   **13.32**   |
|  PGD-50 |   **2.319**   |   0.00  | 0.00   |   0.00   |   0.00  |
|  FFGSM  |   34.94 |   20.30  |  7.90  |   5.63   |   3.91  |


### *L2* attacks
<table>
	<tbody>
		<tr>
			<td></td>
			<td colspan="2"> <b> MNIST </b></td>
			<td colspan="2"> <b> CIFAR10 </b></td>
		</tr>
		<tr>
			<td></td>
			<td>ACC</td>
			<td>Time (s)</td>
			<td>ACC</td>
			<td>Time (s)</td>
		</tr>
		<tr>
			<td>CW</td>
			<td>99.07</td>
			<td>6.47</td>
			<td>0.14</td>
			<td>805.78</td>
		</tr>
		<tr>
			<td>DeepFool</td>
			<td>30.40</td>
			<td>15375.4</td>
			<td>27.68</td>
			<td>46143.5</td>
		</tr>
	</tbody>

</table>

[TBC]




<hr>

* © LIMP & SDAL laboratory
* © Amirkabir University of Technology
