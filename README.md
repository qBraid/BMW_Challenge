# BMW_Challenge

Due to the rapid development of hardware and software, the past decades have
drastically shifted quality control from manual examination towards automated
inspection. In the light of the required human expertise to hand-tune
algorithms, machine learning (ML) techniques promise a more general and scalable
approach to quality control. The remarkable success of convolutional neural
networks (CNNs) in image processing has revolutionized automated quality
inspection. Of course, any technology has its limitation, and for CNNs, it is
computation power. As high-performance CNNs usually assume large datasets,
datacenters ultimately end up with large numerical workloads and expensive GPUs.
Quantum computing may one day break through classical computational bottlenecks,
providing faster and more efficient training with higher accuracy.

Due to the rapid development of hardware and software, the past decades have
drastically shifted quality control from manual examination towards automated
inspection. In the light of the required human expertise to hand-tune
algorithms, machine learning (ML) techniques promise a more general and scalable
approach to quality control. The remarkable success of convolutional neural
networks (CNNs) in image processing has revolutionized automated quality
inspection. Of course, any technology has its limitation, and for CNNs, it is
computation power. As high-performance CNNs usually assume large datasets,
datacenters ultimately end up with large numerical workloads and expensive GPUs.
Quantum computing may one day break through classical computational bottlenecks,
providing faster and more efficient training with higher accuracy.

## Setup

1. Make sure you're using a conda environment with python 3.8.

2. If you don't have one, run this code in your terminal: 'conda create --name
   myenv'

After you have activate your environment, before you install anything, make sure
to update your pip with: `pip install --upgrade pip` 3. 'pip install -r
requirements.txt'

After you have activated your environment, before you install anything, make
sure to update your pip with: pip install --upgrade pip

Please also install the kaggle dataset in a folder called
surface_crack_detection. If you decide on a another name you will have to change
this line `Surface_Data = Path("surface_crack_detection")`

## Install dataset

Given the size of the dataset, please locally install the surface_crack_datset

## Results

```
history = model.fit(trainX_tensor[:1000], trainy_encoded[:1000], validation_data=(testX_tensor[:1000], testy_encoded[:1000]), epochs=10, batch_size=10,verbose=1)
Epoch 1/10
100/100 [==============================] - 1615s 16s/step - loss: 0.5747 - accuracy: 0.7440 - val_loss: 0.4659 - val_accuracy: 0.8370
Epoch 2/10
100/100 [==============================] - 825s 8s/step - loss: 0.4031 - accuracy: 0.8830 - val_loss: 0.3519 - val_accuracy: 0.8880
Epoch 3/10
100/100 [==============================] - 821s 8s/step - loss: 0.3304 - accuracy: 0.9050 - val_loss: 0.3003 - val_accuracy: 0.9190
Epoch 4/10
100/100 [==============================] - 828s 8s/step - loss: 0.2947 - accuracy: 0.9220 - val_loss: 0.2703 - val_accuracy: 0.9200
Epoch 5/10
100/100 [==============================] - 822s 8s/step - loss: 0.2734 - accuracy: 0.9230 - val_loss: 0.2511 - val_accuracy: 0.9370
Epoch 6/10
100/100 [==============================] - 830s 8s/step - loss: 0.2591 - accuracy: 0.9360 - val_loss: 0.2379 - val_accuracy: 0.9430
Epoch 7/10
100/100 [==============================] - 827s 8s/step - loss: 0.2489 - accuracy: 0.9430 - val_loss: 0.2329 - val_accuracy: 0.9490
Epoch 8/10
100/100 [==============================] - 826s 8s/step - loss: 0.2414 - accuracy: 0.9480 - val_loss: 0.2276 - val_accuracy: 0.9400
Epoch 9/10
100/100 [==============================] - 828s 8s/step - loss: 0.2377 - accuracy: 0.9460 - val_loss: 0.2229 - val_accuracy: 0.9430
Epoch 10/10
100/100 [==============================] - 827s 8s/step - loss: 0.2367 - accuracy: 0.9490 - val_loss: 0.2190 - val_accuracy: 0.9470
```

1. Make sure you're using a conda environment with python 3.8.

2. If you don't have one, run this code in your terminal: 'conda create --name
   myenv'

3. 'pip install -r requirements.txt'

After you have activated your environment, before you install anything, make
sure to update your pip with: pip install --upgrade pip

Please also install the kaggle dataset in a folder called
surface_crack_detection. If you decide on a another name you will have to change
this line `Surface_Data = Path("surface_crack_detection")`

## Install dataset

Given the size of the dataset, please locally install the surface_crack_datset

## Results

```
history = model.fit(trainX_tensor[:1000], trainy_encoded[:1000], validation_data=(testX_tensor[:1000], testy_encoded[:1000]), epochs=10, batch_size=10,verbose=1)
Epoch 1/10
100/100 [==============================] - 1615s 16s/step - loss: 0.5747 - accuracy: 0.7440 - val_loss: 0.4659 - val_accuracy: 0.8370
Epoch 2/10
100/100 [==============================] - 825s 8s/step - loss: 0.4031 - accuracy: 0.8830 - val_loss: 0.3519 - val_accuracy: 0.8880
Epoch 3/10
100/100 [==============================] - 821s 8s/step - loss: 0.3304 - accuracy: 0.9050 - val_loss: 0.3003 - val_accuracy: 0.9190
Epoch 4/10
100/100 [==============================] - 828s 8s/step - loss: 0.2947 - accuracy: 0.9220 - val_loss: 0.2703 - val_accuracy: 0.9200
Epoch 5/10
100/100 [==============================] - 822s 8s/step - loss: 0.2734 - accuracy: 0.9230 - val_loss: 0.2511 - val_accuracy: 0.9370
Epoch 6/10
100/100 [==============================] - 830s 8s/step - loss: 0.2591 - accuracy: 0.9360 - val_loss: 0.2379 - val_accuracy: 0.9430
Epoch 7/10
100/100 [==============================] - 827s 8s/step - loss: 0.2489 - accuracy: 0.9430 - val_loss: 0.2329 - val_accuracy: 0.9490
Epoch 8/10
100/100 [==============================] - 826s 8s/step - loss: 0.2414 - accuracy: 0.9480 - val_loss: 0.2276 - val_accuracy: 0.9400
Epoch 9/10
100/100 [==============================] - 828s 8s/step - loss: 0.2377 - accuracy: 0.9460 - val_loss: 0.2229 - val_accuracy: 0.9430
Epoch 10/10
100/100 [==============================] - 827s 8s/step - loss: 0.2367 - accuracy: 0.9490 - val_loss: 0.2190 - val_accuracy: 0.9470
```

## Installation/plugins with jupyter

`nbstripout` is a great option for clearing the output of the jupyter notebooks.
It can be installed using `pip install nbstripout`. For more info see below in
[before you commit section](#beforecommit)

`nbdime` is a great tool for looking at the git diff for jupyter notebooks.

For jupyterlab there is a market place extension which you need to enable first
and that will let you search and install extensions from within jupyter lab. You
can enable the marketplace extension with the following code:

`jupyter labextension install @jupyter-widgets/jupyterlab-manager`

For jupyter notebook, there is a similar extension but that just gets you all
the extension in one go and lets you enable or disable them from the jupyter
home page toolbar. You can install the extension for the jupyter notebook using:
`pip install jupyter_contrib_nbextensions`

`jupyter contrib nbextension install --user`

## <a name="beforecommit"></a> Before you commit or do a pull request:

Since jupyter is not just a text file and uses JSON format, everytime
code/markdown is changed in jupyter notebook, lot of information about the
layout changes as well. This is especially the case for python code which
outputs pictures/graphs. The pictures are stored as text which show up in the
diff. This complicates the git diff. And hence, the best way to version control
jupyter notebooks is by clearing the output before doing a commit. We have been
using nbstripout for clearing output from notebooks automatically. You can
install nbtripout using `pip install nbstripout`. Please make sure to run
`nbstripout notebook.ipynb` to clear the output in a file. To clear the output
in all the notebooks in a given folder, you can run it on a folder, e.g. the
command `nbstripout Qube/*` clears the output from all the notebooks in `Qube`
folder.
