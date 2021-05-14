# dl_fianl_project

## run instruction:
the baisc ipython file dl_final_project.ipython contains example experiments with reduced load test (e.g. only consider two cases for each test scenarios) and output are shown in the notebook. as for convient, the rest ipython files are divided based on the experiment. 

the project contains several experiments exploring different options : 
  1. for the feature extractor comparsion : please run 
  2. for the dropout rate comparsion: please run
  3. for the optimizer comparsion: please run 
  
please note the training requires a model with a specific name which will be generated from the code, one must use the generated name of the model (better use the lowest loss onw) to continue the running.
the example models are uploaded in the model folder, with name convientation as: model_16_Adam_0.1_model.h5 means this is the model for vgg16 optimizer Adam dropout rate 0.1. if anyone wants to use the model rather than self generated one, then must download the model from the folder and use the file location for model input name.
