[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12060769&assignment_repo_type=AssignmentRepo)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/group-assingment-group-2/main)

# 27410 - Group assignment - Group 2- Revolutionizing petrochemical chemistry: bioethylene production in *E. coli*

## Project summary (<300 words)
Ethylene is a molecule that forms the building block for many polymers. It is currently produced by petrochemical means, which has a lot of greenhouse gas emissions associated to it. The aim of the project was to produce ehtylene in a cell-factory, to try to reduce the greenhouse gas emissions. For this we introduced three new reactions into an existing *E. coli* model (iJO1366). The main reaction we were interested in is called ethylene-forming-enzyme main (EFE_m), which converts 2-oxoglutarate and oxygen into ethylene and carbon-dioxide.
We were able to mass- and charge balance the reactions that we added to the model. Therefore the memote scoring remained the same as with the standard iJO1366 model. By adding the reactions we were sucessful in producing ethylene in our model. We were also able to increase the ethylene yield by screening for the most important amino acids and changing the model media accordingly. Unfortunately, further analysis (via OptKnock, FSEOF and manual knock-outs) did not improve our ethylene yield. This contradicts what can be found in literature, where the knock-out of certain genes was shown to improve yield.
This project resembles the 'Design' part of the 'Design-Build-Test-Learn' cycle. The next step would be to build an *E. coli* strain with the added reactions in the laboratory and test whether the *in-vivo* yield matches with the *in-silica* yield.

## Project overview
We have three main folders:
- **models:** Contains the original as well as the modified model.
- **analysis:** Contains all the computational analysis.
- **memote_tests:** Contains the memote reports of all tested *E. coli* models

Outside of these folders the report 'Report.ipynb' can be found. Within the report are the links to the notebooks.
