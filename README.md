# cnn-colorbench
A benchmark study of CNN classification performance on color vs. grayscale images, including data augmentation and efficiency trade-offs.


## Folder Structure
`cnn-colorbench/`
- `main.ipynb`: Jupyter notebook containing the logic to run the experiments (data loading, model training, evaluation).
- `plots.ipynb`: Jupyter notebook for visualizing the results of the experiments.
- `histories/`: Directory containing the training histories of the models.
- `results/`: Directory containing the results of the experiments.
- `saved_models/`: Directory containing the saved models.
- `requirements.txt`: List of required Python packages for the project.

*Note: The `histories/`, `results/`, `saved_models/`,directories are created during the execution of the notebooks and will contain the output of the experiments.*


## Usage
1. Clone the repository:
   ```
   git clone https://github.com/darmangerd/cnn-colorbench.git
   cd cnn-colorbench
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the main experiment:
   ```
   jupyter notebook main.ipynb
   ```

4. Visualize the results:
   ```
   jupyter notebook plots.ipynb
   ```
