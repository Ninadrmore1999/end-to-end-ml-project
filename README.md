# End to End ML projects 
#   create environment 
#   create and link repo on local machine and remote repo on git 
#   create setup.py file with to build ML App as a package
#   create src folder with __init__.py file to create internal package
#   create requirements.txt to install necessary packages
#   pip install requirements.txt and call setup.py to initiate package creation
#   in src create component folder and as always inside component __init__.py file 
#   in component create data_ingestion.py file
#   in component create data_transformation.py file
#   in component create model_trainer.py file
#   this above practise helps to modularize the code
#   now in src create pipeline folder to use modular codes from component to create train_pipeline.py and predict_pipeline.py and __init__.py to make pipeline folder callable
#   in src add logger.py, exception.py and utils.py to take care of logging (log file) activities, handling exceptions/errors and interaction with external web services respectively