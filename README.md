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
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>L1 Name</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>

[TBC]




<hr>

* © LIMP & SDAL laboratory
* © Amirkabir University of Technology
