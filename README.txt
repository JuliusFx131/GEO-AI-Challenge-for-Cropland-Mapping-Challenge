Order of Executing the .ipynb Files:

1.Ensure you are working in the Anaconda environment on your PC. All files provided for this work should be in same location


2.Begin by running the "1.a) Data Extraction Prep -Split Into Countries.ipynb" file first.


-This step is necessary to generate the each country's train and test csv files, which are used in the subsequent "1.b) Data Extraction - Final Step_(NOT COLAB).ipynb" file.

3. Proceed to run the "1.b) Data Extraction - Final Step_(NOT COLAB).ipynb" file.

-This step is necessary to pull sentinel bands for each country for both train and test files 


4. Proceed to run the "2.e) GRIDSEARCHED - 0.913.ipynb" file.


5. For the final submission on Zindi, use the output from the last step, specifically the "1.lgbm.csv".