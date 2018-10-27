# <center>How to use Google Colab for the course Praktikum Neuronale Netze </center>

Google Colab (https://colab.research.google.com) is a FREE cloud service to run jupyter-like notebooks. It provides free GPUs (K80 at the moment of this writing) and TPUs (Google GPU-like processing units optimized to run Deep Learning codes). The documents (mostly notebooks) are stored in your Google Drive, so **it is required that you have a Google Drive account**.    

There is an awesome, easy-to-follow tutorial about Google Colab at the end of this, feel free to read it after finish setting up everything.
 
The problem of Google Drive when a folder being shared is that we cannot make a copy of the whole folder and  automatically follow the updates on that folder. So the following way of sharing is quite *inconvenient*, but I haven't figured out a better way at the moment. I shared the Google Colab version of the Praktikum in our ILIAS forum. Clicking to that link will open the folder in your Drive.

1.  Download the whole zipped Praktikum to your computer, extract it to the folder PraktikumNeuronaleNetze
2.  New -> Folder to create a folder dedicated for your Google Colab, e.g. Colab\_Notebooks.
3.  Then New -> Folder upload and choose your unzipped PraktikumNeuronaleNetze to upload to your Google Drive.
4.  If PraktikumNeuronaleNetze is outside of your Colab\_Notebooks folder, move it into that folder. Your PraktikumNeuronaleNetze folder would contain Images folder, Data folder and Week1\_NumpyTutorial with files inside each folder.
5.  Go to a notebook, e.g Week1\_NumpyTutorial > PNN\_Numpy\_Tutorial.ipynb, you cannot open it as a notebook for the first time, you need to associate your notebooks with Colaboratory: 
    *  Click to "Open with", choose "Connect more apps"
    *  "Connect more apps" Dialog appears, on textbox "Search Apps", type Colaboratory and click the blue button "CONNECT"
    *  Now instead of "Open with" every time you open a notebook, you will have the default "Open with Colaboratory".
6.  Now you can run the notebooks, change the code and have Drive takes care of version control for you.
7.  Whenever I post new files (either image files in Images folder, new dataset files in Data folder, or new files/folders for the coming weeks), unfortunately, you have to update your PraktikumNeuronaleNetze manually by downloading my files and uploading them one by one to the correct places (or using "Make a Copy" for every new files and moving them to the correct places).

The steps from 1-6 you would need to do them once, but you have to do the step 7 every time I posted new files (often once every week).

### The awesome link: https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d

You have to mount your Drive to your Google Colab environment to have access to external files (e.g. dataset files) every session. Just run the code below. You will see it at the first code cell on the notebook Week1\_NumpyTutorial > PNN_Ex_LogisticLQRegression.ipynb. You have to run it when you start (or restart) every session:

```python
from google.colab import drive
drive.mount('/content/drive')
```

Notice to the correct path of the files and folders you want to access after mounting your Drive. You can use this code in your Colab notebooks to check before accessing:

```python
import os
os.path.isfile("drive/My Drive/Colab_Notebooks/data/mnist_seven.csv") # file to use
```

There are some differences from the github version of the Praktikum and the Google Colab. Some of them are from the different versions of Python and Python libraries. Others are from the paths of the resources. If you have any problem running the codes, do not hesitate to ask in the forum or email to me [thanh-le.ha@kit.edu](mailto:thanh-le.ha@kit.edu) 
