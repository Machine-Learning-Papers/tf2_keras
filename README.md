
## [Check our Zero To Deep Learning 5 day bootcamp. New dates are out!](https://www.zerotodeeplearning.com/?utm_source=github.com&utm_medium=affiliate&utm_campaign=https%3A%2F%2Fgithub.com%2Fzerotodeeplearning%2Ftf2_keras&utm_content=README.md)

-----------------------



# Tensorflow 2.0 and Keras: what's new, what's shared, what's different
Repository for the talk on Tensorflow 2.0 and Keras: what's new, what's shared, what's different.

[Slides](http://bit.ly/2Wd9xpu)

## Quick start guide

#### Download and install Anaconda or Miniconda Python 3

Download [Anaconda](https://www.anaconda.com/distribution/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) and then install it on your system.


#### Open a terminal

#### Clone this repository on your local computer
```
git clone https://github.com/zerotodeepearning/tf2_keras.git
```

#### Change to course folder
```
cd tf2_keras
```

#### Create Conda environment

We provide an [environment configuration file](environment.yml) with all the required dependencies.

```
conda env create
```

wait for the environment to create, this may take a few minutes. Note that this environment is based on Python 3.6 because Tensorflow does not support Python 3.7 yet.

#### Activate the environment (Mac/Linux)
```
conda activate tf2_keras
```

#### Activate the environment (Windows)
```
activate tf2_keras
```

Check that your prompt changed to

```
(tf2_keras) $
```

Now you can run jupyter notebook from within the environment.

#### Launch Jupyter Notebook
```
jupyter notebook
```
and access it from your browser at: http://localhost:8888

You are good to go! Enjoy!


### Troubleshooting

#### Updating the environment
If you have previously created the environment and want to update it with the current env file type:
```
conda env update
```

#### Updating Conda

If you have installed Anaconda a long time ago, you may want to update it by running:
```
conda update conda
```
and then:
```
conda update anaconda
```

#### Deactivating the environment (Mac/Linux)
```
conda deactivate
```

#### Deactivating the environment (Windows)
```
deactivate
```

#### Deleting the environment
If you decide to completely delete the environment from your system you should use the following command:
```
conda remove -y -n tf2_keras --all
```
