# Random-Forest-Node-Embedding
The is the code repo. for the article which published on Expert Systems with Application: 
"Personalizing Communication and Segmentation with Random Forest Node Embeddings,", Capsule number: 894c87aa-303f-480e-8b97-532184efe93f from code ocean. 

In this study, we developped a novel approach, called random forests node embeddings (RFNE), to model categorical and continuous features by calculating node embeddings on the decision trees identified with a random forest algorithm. This experimentation
shows that using embeddings calculated on a random forest is an effective method of extracting automated features for classification. This  The  novelty of  this algorithm stands in  the usage of the structure of the decision boundaries  calculated by the decision trees as additional features in the  form  of embeddings that can be used  to perform  machine learning  tasks. Furthermore, this approach makes the classification more flexible  task  more flexible than with a  standard  random forest  algorithm as one can now use any algorithm
in combination with random forests. The other significant contribution the features  extracted by RFNE. The second  main  contribution of this paper is to show that by using the latent space features calculated with the embedding embeddings, we can define segmentation rules concerning a population of interest. The consequence of using a random forest to calculate the embeddings is that the nodes of the forest have also a representation in the latent space. Therefore, if we take an interesting question as our dependent variable for a statistical test.

You can find the full published article link: https://www.sciencedirect.com/science/article/pii/S095741742401488X

# Clone the repo:

git clone https://github.com/weiweivv2222/Random-Forest-Node-Embedding.git

# Change directory into the project folder
cd your_project_name

# Create a virtual environment
conda create -m your_project_name

# Activate the virtual environment
# On Windows
.\env\Scripts\activate
# On Unix or MacOS
source env/bin/activate

# Install the required packages
pip install -r requirements.txt

change the data_path to your data location


├── README.md              # This file

├── requirements.txt       # List of dependencies python packages


├── scripts                         # Folder containing scripts and notebooks
 
│   ├── Duke_D2_git.ipynb           # Jupyter notebook for Duke_D2 analysis

    
│   ├── Duke_D2_reduce.ipynb        # Jupyter notebook for reducing Duke_D2, which is the example running code in code ocean platform

│   ├── KDDCup_D3_git.ipynb         # Jupyter notebook for KDDCup_D3 analysis

│   ├── NodeTransformer.py          # Python helper script for node transformation that is used to construct RFNE

│   ├── NodeTransformerExtremeTrees.py  # Python helperscript for extreme trees transformation

│   ├──Portugal_D1_git.ipynb       # Jupyter notebook for Portugal_D1 analysis

└── data                   # Folder containing data files          
 

