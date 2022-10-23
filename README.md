https://github.com/kennguyen0303/COMP_472_F2022_K2-  
  
# Instructions
To run this program, you will need to install a few packages such as `numpy`, `sklearn`, `matplotlib`, `gensim`, `pandas`, `seaborn` and `itertools`, along with dataset **goemotions.json.gz**.

This program is divided in 4 separate notebooks, so that each notebook can be run independently of each other. 
  
### `mini_project_1.ipynb`
This is the main notebook that covers data processing and features extraction. This notebook also contains the classification tasks using embeddings as features.  

The project tasks covered in this notebook are:
1. Dataset preparation & analysis  
    1.1 - 1.3 Dataset loading and distribution plots
2. Words as Features   
    2.1 Words extraction using `CountVectorizer`, and word frequencies  
    2.2 Training and testing sets split
3. Embeddings as features
    
The other 3 notebooks list down the coverage based on the tasks assigned to the owner.
    
### `mini_project_kevins_notebooks.ipynb`
This notebook covers the subtasks:  
- 2. Words as features  
    - 2.1 Words extraction using `CountVectorizer`, and word frequencies  
    - 2.3 Training and testing
        - 2.3.1 Base MNB  
        - 2.3.5 Top decision tree  
    - 2.4 Performance of the models  
    - 2.5 Stop words removal  
- 3. Embeddings as features  
    - 3.1 word2vec model loading  
    - 3.2 Words extraction using `tokenizer`  
    - 3.3 Embeddings computing  
    - 3.4 Hit rates computing  
    
### `mini_project_ken_notebook.ipynb`
This notebook covers the subtasks:
- 2. Words as Features   
    - 2.2 Training and testing sets split  
        - 2.3.2 Top MNB
        - 2.3.4 Base decision tree
    - 2.4 Performance of the models  
    - 2.5 Stop words removal
- 3. Embeddings as features 
    - 3.5 Base MLP
    - 3.7 Display performance
    - 3.8 2 other pretrained embedding models

### `MP1-Vata.ipynb`
This notebook covers the subtasks:
- 1. Dataset preparation & analysis  
    - 1.1 - 1.3 Dataset loading and distribution plots
- 2. Words as Features   
    - 2.3 Training and testing  
    - 2.3.3 Base MLP  
    - 2.3.6 Top MLP
    - 2.4 Performance of the models  
    - 2.5 Stop words removal
- 3. Embeddings as features 
    - 3.6 Top MLP
    - 3.7 Display Performance