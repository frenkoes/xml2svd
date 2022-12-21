# xml2svd
Generate svd file (which can be used by svd2rust) for the f28388d cm core. 

# SVD tools found
 * tixml2svd: can be used to generate a first svd file from the xml files provided by TI
 * svd2rust: is used to generate code from a svd file
 * svdtool: is used to patch the svd file. (do not know if I need this yet)
 * cmsis-svd: can be used to make own python parser. 

# Steps to be taken:
 1. Find xml files which can be used to generate a svd file
 2. Generate svd file for the CM core. 
 3. Check if entries of the svd file corresponding to the ones that are in a datasheet.
 
