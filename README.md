# Extending-an-RNA-sequencing-pipeline-to-enable-and-utilize-high-sample-numbers
To run trimmosumary you need:

Python 2.7 and packages: os, re, zipfile,sys and numpy.

R (preferably  3.2.2, but anything from 3.1 on should work) and packages ggplot2.

Instructions to run:

1. You need to have the 3 scripts in the same folder.
2.Make sure the scripts have execution, reading and writing permissions (I used chmod 777).
3.Run the masterscript using the following line:
>>python trimmosumary.py <Inpunt folder> <Output folder>
Examples:
>>python trimmosumary.py some_input_folder/ some_output_folder/
>>python trimmosumary.py 1_sequence_and_mapping_quality/ Print/

Note that the separator between both arguments is a space and that both folders should end with "/".
