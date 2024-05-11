# MultiLabel Stream Classification

## Overview
This repository contains the implementation of neural network models for multi-label classification in streaming data. The project focuses on evaluating the effectiveness of the replay method in neural networks to enhance generalization and combat catastrophic forgetting in streaming setups. A detailed comparison with Recurrent Neural Networks (RNN) is also explored, highlighting the benefits of each approach in the dynamics of data streams.

## Key Features
- **Streaming Multi-label Classification**: Utilizes advanced neural network models for dynamic and stationary data streams.
- **Continual Learning and Catastrophic Forgetting**: Implements the replay method to address catastrophic forgetting, ensuring model adaptability over time.
- **Experimentation with RNNs**: Incorporates LSTM cells for handling dependencies in data sequences, suitable for real-time streaming data.

## Getting Started
To run the models and experiments provided in this repository, follow these steps:

### Prerequisites
- Python 3.8+
- Libraries as specified in `requirements.txt`

### Installation
Clone the repository and install the required libraries:
```bash
git clone https://github.com/d1azox/MultiLabelStreamClassification.git
cd MultiLabelStreamClassification
pip install -r requirements.txt
```
### Running the Notebook

Ensure you are in the project directory and then start Jupyter Notebook to access the notebook_20NG.ipynb:

```bash
jupyter notebook
```

### Experiments and Results

The project evaluates various configurations and their impact on the performance of multi-label streaming classification. The results demonstrate significant improvements in the Jaccard index, emphasizing the importance of adaptive techniques in continual learning.

For detailed information on the experiments and their outcomes, refer to the provided Jupyter notebook.

### References

1.	Wang, X. (2023). Classification Multi-Labels en flux: comparaisons d'approches et nouvelles propositions. [Doctoral dissertation, Nantes Université]. HAL Archives. Available at: https://theses.hal.science/tel-04107514v1
2.	Roseberry, M. (2024). Adaptive Multi-label Classification on Drifting Data Streams. [Virginia Commonwealth University]. Scholars Compass. Available at: https://scholarscompass.vcu.edu/cgi/viewcontent.cgi?article=8697&context=etd
3.	van de Ven, G. M., Soures, N., & Kudithipudi, D. (2024). Continual Learning and Catastrophic Forgetting. Available at: https://arxiv.org/pdf/2403.05175
4.	Montiel, J., Halford, M., Mastelini, S. M., Bolmier, G., Sourty, R., Vaysse, R., ... & Bifet, A. (2021). River: machine learning for streaming data in Python. Journal of Machine Learning Research, 22(2021), 1-8. Available at: https://www.jmlr.org/papers/volume22/20-1380/20-1380.pdf
5.	Wang, X., Kuntz, P., Meyer, F., & Lemaire, V. (2021, December). Multi-Label kNN classifier with Online Dual Memory on data stream. In 2021 International Conference on Data Mining Workshops (ICDMW) (pp. 405-413). IEEE. Available at: https://ieeexplore.ieee.org/document/9679913
6.	Wang, X., Meyer, F., Kuntz, P. (2023). Formalisation de la classification multi-Labels en flux et son application en cybersécurité : une étude approfondie. Available at: https://pfia23.icube.unistra.fr/conferences/rjcia/Actes/RJCIA2023_paper_14.pdf
