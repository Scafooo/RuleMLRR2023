# GATE

## Installation
 
Download the latest version of GATE from: [link Gate](https://gate.ac.uk/download/)

Start GATE, note that on MACOSX you must start it from the terminal to give the tool permissions to read the directory.

Assuming GATE is in Applications run the following commands:

```
cd Applications/GATE_Developer_9.0.1
sudo GATE.app/Contents/MacOS/GATE
```

Create a new corpus, right-click on language resources->create new corpus.

Right-click on the newly created corpus and select Populate.
Select the Corpus folder attached to this guide and wait for it to populate.

## Loading Resources.
* Select File->New Processing Resources->Add Annie Resources to this Menu.
* Right-click on Processing Resources->Document reset PR.
* Right-click on Processing Resources->GATE Unicode Tokenizer.
* Right-click on Processing Resources->Annie Gazzetter->(select the gazzetter folder and the file main.lst).
* Right-click on Processing Resources->JAPE Transducer->select the main.jape file in the JAPE folder.
* Right-click on Processing Resources->JAPE Plus->select the main.jape file of the JAPE folder.

## Pipeline creation.
* Right-click on Applications->create new Applications->Corpus Pipeline.

Select the components in order by moving from the left selection box to the right selection box: Document reset PR, GATE Unicode Tokenizer, Annie Gazzetter, JAPE Transducer. Start on the corpus, the results in terms of timing can be seen in the bottom left window.

To run the tests with JAPE Plus perform the previous step but select JAPE Plus instead of JAPE Transducer.

For the RAM and CPU utlized use the VisualVM program with administrator permissions.

For ease we report the performance related to CPU and RAM through the following plots.

##RAM
![]()

##CPU
![]()