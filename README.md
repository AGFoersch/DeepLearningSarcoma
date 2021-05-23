# DeepLearningSarcoma
This is the Github Repo to the research paper **"Deep learning for diagnosis and survival prediction in soft tissue sarcoma"** by Foersch et al. Detailed code examples and a sample dataset will be made available shortly. In the meantime, feel free to inquire about this project to our group [here](mailto:sebastian.foersch@unimedizin-mainz.de?subject=[GitHub]Deep%20Learning%20Sarcoma) :microscope::man_health_worker::desktop_computer:
## Introduction
:building_construction: Under construction (summary of the findings and abstract here) :building_construction:

Soft Tissue Sarcoma (STS) are rare tumors, which are particularly difficult to diagnose. This is usually done by pathologists, who (after ruling out other entities) further subdivide STS into further subtypes. These subtypes have varying prognoses and require different types of treatment. So classifying STS subtypes is really important in the clinical management of this disease. Therefore we trained a deep learning model to distinguish between the five most common STS subtypes. In this Github Repo you will find a jupyter notebook to recreate the training that was done within this project on some example data. You can either use the built-in fast.ai evaluation (as is done in the notebook) or implement your own evaluation code based on the training outcome.
## Requirements
:man_factory_worker: Under construction (libraries with versions here) :man_factory_worker:

python >=3.6<br/>
fastai 1.0.57 (v1)<br/>
matplotlib 3.1.3<br/>
pandas 1.1.5<br/>
torch 1.4.0<br/>
torchvision 0.5.0<br/>
Pillow 7.0.0<br/>
sklearn 0.23.1<br/>

## How to use the code
:construction: Under construction (tutorial with iPython notebook here) :construction:

To use the code the requirements mentioned above need to be installed. Furthermore, all calculations were done on a Titan RTX, so it is highly recommended you use a similar or better GPU for your experiments. The example code is easy to use and straight forward - simply follow the ipython notebook and adjust it to your setup / question. In our example, the key.csv file contains the patient_ID, which is important to get patient based metrics, the path to where the images of that case are stored, the label, a column denoting whether the image belongs to the TRAIN, VALID, or TEST set and another boolean value "is_valid" for only the validation cases. This setup can easily be changed however, to fit your individual requirements. For further information make sure to check out the markup text within the notebook.

(Note: The examples provided in this Github Repo will not be sufficient to reach the levels of performance achieved in our paper. They are just included for you to be able to get the code up and running. The images have already been normalized to a reference image using structure preserving color normalization (SPCN)).

## How to cite the paper
:construction_worker_woman: Under construction (reference here) :construction_worker_woman:
## Contact
Dr. Sebastian Foersch  
Institute of Pathology  
University Medical Center Mainz  
Langenbeckstr. 1  
55131 Mainz, Germany
