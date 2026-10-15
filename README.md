# Sleep-Disorder

Sleep Disorder Prediction using Deep Learning.

## 1. Install Python
Download Python from the official website:
https://www.python.org/downloads/

During installation, select **Add Python to PATH**.

Verify the installation:
`ash
python --version
`

## 2. Install Required Packages
`ash
python -m pip install gradio mne numpy pandas
`

## 3. Upgrade pip
`ash
python -m pip install --upgrade pip
`

## 4. Install Legacy Keras Compatibility
`ash
python -m pip install tf-keras==2.20.1
`

## 5. Check Dependency Conflicts
`ash
python -m pip check
`

## 6. Display Installed Packages
`ash
python -m pip list
`

## 7. Check TensorFlow and Keras Versions
`ash
python -c "import tensorflow as tf; import tf_keras; print('TensorFlow:', tf.__version__); print('tf_keras:', tf_keras.__version__)"
`

## 8. Test the Saved Model
Run this from the project root:
`ash
python -c "import tf_keras; m=tf_keras.models.load_model('GUI/healthy_cap_new.h5', compile=False); print('Model loaded successfully')"
`

## 9. Run the DeepNap Application
`ash
python GUI/gradio_app.py
`

Open the local URL displayed in the terminal in your browser.

## Project Files
- GUI/ — training scripts, saved models, evaluation results, and the Gradio application.
- Large datasets are stored separately and will be shared through an external link.

## Dataset
The large datasets are not included in this repository. A Google Drive link will be added here.


In sleep-disorder-prediction folder create data folder and place the datasets

Balanced and Unbalanced:
https://www.kaggle.com/datasets/shrutimurarka/cap-sleep-unbalanced-dataset?select=Balanced+Data


Healthy and unhealthy: https://drive.google.com/drive/folders/1ai3kodudyjBxSH4zHm5dwUSmWSDUL2eB

Disorder phases
https://drive.google.com/drive/folders/1tQHZx3aY3X9Us2UIJBVAjlLs15oIcgEF
