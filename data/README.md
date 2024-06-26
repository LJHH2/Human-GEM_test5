# Human-GEM data

This directory contains datasets, metabolic task files, and log files that support some functionality of Human-GEM and its associated scripts, and/or were used for the generation and curation of Human-GEM. The data subdirectories and their contents are briefly summarized below.

### metabolicTasks
Contains metabolic task files used for evaluating the functionality of Human-GEM.
- `metabolicTasks_Essential.xlsx`: Metabolic tasks that are necessary for cell viability.
- `metabolicTasks_Full.xlsx`: A longer list of metabolic tasks which contains some functions that may not be relevant for all cell or tissue types. However, all of these tasks should pass for the generic Human-GEM.
- `metabolicTasks_VerifyModel.xlsx`: Metabolic tasks designed to verify that the model is properly mass and energy balanced, and exhibits a biologically meaningful solution space.

### modelCuration
Contains curation-related data files used for making changes to the Human-GEM model. These model curation data files help to improve transparency of changes made to the model.

Note that many of the data files associated with model curation were outdated and not maintained, and have been moved to the `.deprecated` folder in the root directory of this repository.

### deprecatedIdentifiers
Contains the `tsv` files with reaction and metabolite annotation, identical to that in `/model/` for those identifiers that have been used in Human-GEM and subsequently removed. The identifiers are kept here so as to avoid accidentally reusing them in the future.