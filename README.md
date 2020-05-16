# magpix-average-script
Input File:
-	Format: .csv file
-	Sample name format: IgG_S00123
-	Samples do not have to be in chronological order
-	One tab only! 
-	Headers: can be in any format, but should be in the format you want your output file to be in 
Output File:
-	Format: .csv file
-	The output file will be saved in the directory you are working from 
Note: after creating your output file, import the file into an excel sheet and save as an excel document. This will prevent any format errors since the .csv file is comma delimited. 

Running the script:
-	Run the script from your command line in the directory of your script and files 

python medianaveraging.py

-	The script will ask user input for the output file name and the input file name. Make sure to add ‘.csv’ at the end of the file name. 
KIMBERLYs-MacBook-Air:MFI average KCELONA$ python medianaveraging.py 
Type output filename: NHPallcollected_output.csv
Type input filename: 20181219_Allcollecteddata_forscripttrial_KRC.csv
KIMBERLYs-MacBook-Air:MFI average KCELONA$ 

Other details:
-	The script can take multiple replicates. 
-	Currently, the script can only handle .csv files. 

