# BMW_Challenge
   Due to the rapid development of hardware and software, the past decades have drastically shifted quality control from manual examination towards automated inspection. In the light of the required human expertise to hand-tune algorithms, machine learning (ML) techniques promise a more general and scalable approach to quality control. The remarkable success of convolutional neural networks (CNNs) in image processing has revolutionized automated quality inspection. Of course, any technology has its limitation, and for CNNs, it is computation power. As high-performance CNNs usually assume large datasets, datacenters ultimately end up with large numerical workloads and expensive GPUs. Quantum computing may one day break through classical computational bottlenecks, providing faster and more efficient training with higher accuracy.




After you have activate your environment, before you install anything, make sure
to update your pip with: pip install --upgrade pip

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

