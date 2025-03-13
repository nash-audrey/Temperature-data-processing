# Temperature-data-processing
Jupyter notebook with instructions for processing raw data from tetrode recordings, as well as .pickle files containing lick information and neural spiking information for 433 neurons

This notebook is written with a particular file organization system in mind. TempDataProcessing.ipynb ultimately takes information from many .csv files and writes it into convenient DataFrames for further analysis. Then, these DataFrames are written to .pickle files saved in the .zip folder. The second notebook, TempDatChecking.ipynb, checks that the .pickle files were written correctly, can be opened, and confirms that the data processing was consistent with the method proposed for some trials by the lab.


The summary CSV file should contain two columns, one with the unique mouse name/identifyer and one with the date. these combinations should be unique and not repeat.
