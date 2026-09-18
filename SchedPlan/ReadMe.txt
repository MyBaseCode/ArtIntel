The programs were developed using Python and Jupyter Notebook.

Required Python libraries:

numpy
pandas
scikit-learn
matplotlib

The notebooks use the CSV datasets located in the data/ directory.

If the required Python libraries are not already installed on the ECS
machines, they can be installed using:

pip3 install numpy pandas scikit-learn matplotlib

Part 1 is a question-and-answer style assignment and does not require
the Scheduling notebook.

Therefore, Scheduling.ipynb is NOT required for Part 1.

The answers for Part 1 are provided in the submitted report PDF.

The Perceptron.ipynb notebook contains the implementation and
experiments for the perceptron tasks.

It includes:

Task (a):
    Perceptron on the linearly separable SeaSyn dataset.

Task (b):
    Perceptron on the non-linearly separable RingSyn dataset.

The datasets used are:

data/SeaSynTrain.csv
data/SeaSynTest.csv
data/RingSynTrain.csv
data/RingSynTest.csv

To run the notebook from the command line, start Jupyter Lab:

jupyter lab

Then open:

Perceptron.ipynb

Run all cells in order.

The notebook will print the training and test accuracy for each
number of epochs.

The tested epoch values are:

1, 5, 10, 15, 20, 50, 60, 80, 100, 120, 150, 200

The MLP.ipynb notebook contains the implementation and experiment
for Task (c).

The MLP uses scikit-learn's MLPClassifier and is trained on the
RingSyn dataset.

The notebook tests one hidden layer with between 4 and 10 neurons.
The training and test accuracy are printed for each configuration.

To run the notebook:

jupyter lab

Then open:

MLP.ipynb

Run all cells in order.

The generated accuracy graph is saved as:

MLPPerform.png

The configuration with 9 hidden neurons achieved the highest test
accuracy in the experiment.

The report is located in:

Report/A3/PlanningSchedulingNN.pdf

The LaTeX source files used to generate the report are also included
in the Report/A3/ directory.

Scheduling.ipynb is included in the submission but is NOT required
for Part 1.

Part 1 is a question-and-answer style assignment, and therefore the
Scheduling notebook does not need to be executed when marking Part 1.

All required datasets are provided in the data/ directory.

The datasets are:

SeaSynTrain.csv
SeaSynTest.csv
RingSynTrain.csv
RingSynTest.csv

The notebooks expect the data directory to be located in the same
directory as the notebooks.

Perceptron on SeaSyn:

Epochs:   1, Test Accuracy: 0.6250
Epochs:   5, Test Accuracy: 0.7000
Epochs:  10, Test Accuracy: 0.6000
Epochs:  15, Test Accuracy: 0.8500
Epochs:  20, Test Accuracy: 0.6250
Epochs:  50, Test Accuracy: 0.6500
Epochs:  60, Test Accuracy: 0.6000
Epochs:  80, Test Accuracy: 0.6250
Epochs: 100, Test Accuracy: 0.6250
Epochs: 120, Test Accuracy: 0.6750
Epochs: 150, Test Accuracy: 0.7500
Epochs: 200, Test Accuracy: 0.7500

Perceptron on RingSyn:

Epochs:   1, Test Accuracy: 0.6567
Epochs:   5, Test Accuracy: 0.6567
Epochs:  10, Test Accuracy: 0.7200
Epochs:  15, Test Accuracy: 0.6567
Epochs:  20, Test Accuracy: 0.6567
Epochs:  50, Test Accuracy: 0.7500
Epochs:  60, Test Accuracy: 0.6567
Epochs:  80, Test Accuracy: 0.6567
Epochs: 100, Test Accuracy: 0.6567
Epochs: 120, Test Accuracy: 0.6567
Epochs: 150, Test Accuracy: 0.6567
Epochs: 200, Test Accuracy: 0.6567

MLP on RingSyn:

Hidden neurons: 4,  Test Accuracy: 0.9133
Hidden neurons: 5,  Test Accuracy: 0.9333
Hidden neurons: 6,  Test Accuracy: 0.9233
Hidden neurons: 7,  Test Accuracy: 0.9233
Hidden neurons: 8,  Test Accuracy: 0.9233
Hidden neurons: 9,  Test Accuracy: 0.9433
Hidden neurons: 10, Test Accuracy: 0.9100

No known bugs.