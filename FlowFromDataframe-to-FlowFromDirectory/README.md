# FlowFromDataframe-to-FlowFromDirectory

This piece of code converts a categorical image dataset with a CSV to multi directory dataset supported keras's FlowFromDirectory method.

* In this approch i had eye fundus images from kaggle compitition of detecting diabetic retinopathy. Data comes with a csv file which provides additional information to dataset

* Converting a single catagorical dataset (which uses keras's FlowFromDataframe method) to a multi directory dataset (which uses keras's FlowFromDirectory method) with use of csv provided and also made by initial preprocessing.

## Workflow
```
it's quite simple ...

we have data in 5 catagories
0 - No DR
1 - Mild
2 - Moderate
3 - Severe
4 - Proliferative DR

workflow of separating images according to their
severity and storing them in separate folder:

1: load csv and store labels in a separate list
   according to catagories.
2: move the listed label's photos to new catagorical
   folders
```
  
#### NOTE : Skimming over the code you'll see that i have rename the files to move them to directory (reason in code). skip the renaming part if you dont need as it's quite time consuming.





##                                 *I'm still learning feel free to criticize.*
