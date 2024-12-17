# Official Repository for "Unlocking quantum SVM potential: optimal feature map generation and feature selection"

This repository contains the official code and supplementary materials for the paper:

**Unlocking quantum SVM potential: optimal feature map generation and feature selection**  
Published in *Physica Scripta*, available at: [https://iopscience.iop.org/article/10.1088/1402-4896/ad9e39](https://iopscience.iop.org/article/10.1088/1402-4896/ad9e39).

## Abstract
The study proposes a mechanism to generate effective feature maps with optimal feature selection using the Tabu Search algorithm. It compares the performance of classical support vector machines (SVM), quantum support vector machines (QSVM) with only gate selection, and QSVM with both gate selection and feature selection (QSVM-FS) across various datasets. The results indicate that classical SVMs excel with several benchmark datasets, while QSVMs show superior performance on synthetic datasets with non-linear separability. Notably, QSVM-FS consistently outperforms basic QSVM, highlighting the importance of feature selection in enhancing model accuracy. These findings suggest that while both quantum and classical SVMs have unique advantages, quantum methods offer particular benefits in specific scenarios. In the NISQ era, classical simulations are a primary tool for assessing quantum experiments, though they face challenges such as design impacts, limited scales, and biases. Ultimately, no definitive winner exists between quantum and classical methods, as both have their own strengths.


To be updated
## Contents of the Repository
- `src/`: Contains the implementation of the algorithms and experiments discussed in the paper.
- `data/`: Includes any datasets used for validation or testing.
- `notebooks/`: Jupyter notebooks for reproducing the main results and figures from the paper.
- `docs/`: Supplementary documentation and additional resources.
- `README.md`: This file.

## Requirements
To replicate the experiments or run the code, ensure you have the following dependencies installed:
- Python 3.x
- [List any required libraries, e.g., NumPy, SciPy, TensorFlow, etc.]

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Reproducing Results
Follow these steps to reproduce the results:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/official-repo.git
   cd official-repo
   ```
2. Run the main script or Jupyter notebook provided in the `notebooks/` directory.

## Citation
If you use this repository or code in your research, please cite our paper:

```
@article{10.1088/1402-4896/ad9e39,
	author={Zahid, Sumaiyah and Tahir, Muhammad Atif},
	title={Unlocking quantum SVM potential: optimal feature map generation and feature selection},
	journal={Physica Scripta},
	url={http://iopscience.iop.org/article/10.1088/1402-4896/ad9e39},
	year={2024},
	abstract={The study proposes a mechanism to generate effective feature maps with optimal feature selection using the Tabu Search algorithm. It compares the performance of classical support vector machines (SVM), quantum support vector machines (QSVM) with only gate selection, and QSVM with both gate selection and feature selection (QSVM-FS) across various datasets. The results indicate that classical SVMs excel with several benchmark datasets, while QSVMs show superior performance on synthetic datasets with non-linear separability. Notably, QSVM-FS consistently outperforms basic QSVM, highlighting the importance of feature selection in enhancing model accuracy. These findings suggest that while both quantum and classical SVMs have unique advantages, quantum methods offer particular benefits in specific scenarios. In the NISQ era, classical simulations are a primary tool for assessing quantum experiments, though they face challenges such as design impacts, limited scales, and biases. Ultimately, no definitive winner exists between quantum and classical methods, as both have their own strengths.}
}
```


## Contact
For any questions or feedback, please contact:
Sumaiyah Zahid (sumaiyah@nu.edu.pk)
