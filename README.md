# Predicting student loan approval using a Decision Tree classifier and a Random Forest classifier

## To replicate:
1. Download .ipynb file
2. Downlaod .csv file
3. Upload to Jupyter Notebook or Google Colab
4. Run

   * "Using Git" and "Using Libraries" cells are simply informational, no need to run
   
   * The dataset importation method this notebook uses is through Google Drive. To do this, you upload the .csv file to Google Drive and run "Import Dataset" cell.
   
   * If you do not want to upload to Google Drive, there is no need to run "Import Dataset". You must then change the file path in Main in this line to your path:

      df = pd.read_csv('/content/drive/MyDrive/loan_approval_dataset.csv')
   
   * Run Main

## Interpreting Results

** Results may vary from run-to-run as the random test data varies **

There are many labeled graphs provided to visualize effects, all of which have comment code indicating where they came from and what they compare/show.

After multiple runs, it is evident that income, assets, and cibil score have the greatest effect on loan approval.
