Note for future reference

I tried to set up tensor flow for GPU on my desktop

I am using the conda envirornment TnsrFlwGPUenv alongside my existing venv env

conda install -c conda-forge cudatoolkit=11.2 cudnn=8.1.0

# Verify the installation:
python -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"
