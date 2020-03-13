# Setup and usage description for Studies protocol to upload endpoint assay data

## Usage
* Data submission must be in .xlsx or .csv formats.
* Use the [template](template.xlsx) file to fill in your submission and maintain the column order at all times.
* You can refer to [this](example_submission.xlsx) file for an example submission.
* Create new experiment in Endpoint Data protocol, type in a name and description.
* In Data Upload section click on '+' to upload the data.
* Check if your browser is not blocking pop up for processing script selection (applies for first time users of the protocol).
* Review if data is parsed correctly and approve.
* Upload any other relevant associated files or notes.
* Complete the experiment in Studies once finished with the submission to expose it to other Browser forms since they only should be showing completed experiments.
* Different experimental runs must be submitted as separate Studies experiments instead of mashing submission up into one.
* You can delete the submission by deleting the associated document. The data associated will get removed too.

## Template column description
(R) marks required columns to fill in.
* (R) sample_id - an identifier for a sample tested e.g. compound ID.
* (R) sample_batch - sample batch number. You should always record batch ID for a compound or biological entity. The only exception can be sequence expressions and can be recorded as 0.
* eln_id - ELN ID to link experiment with ELN records. Should be always applicable for in-house experiments.
* test_id - a test ID of an assay. Used to distinguish between different repeated runs, especially if done on the same date.
* study_type - type of the study assay is associated with e.g. KINASE or ADME or PROTEIN-PROTEIN INTERACTION.
* (R) target - the name of the target. In case of ADME assay recorded as ADME, if it's a cell line - record it here
* gene - if target is a protein or protein complex please specify a respective gene(s), separated by a dash e.g. JAK2-TYK2.
* organism - specify target species in Latin.
* cell_line - if cell based assay specify cell line used. In case target is a cell line you end up recording cell line twice. You can refer to ATCC for offical names of cell lines.
* (R) assay_name - name of the assay or protocol.
* assay_type - type/category of the assay.
* (R) result_type - result type e.g. IC50, Primary Screen.
* result_modifier - modifier describing numerical result e.g. '>' or '='
* result_numeric - numerical value of the assay result.
* (R) result_alpha - full result value. This should be a combination of result_modifier and result_numeric. In case modifier is absent result_numeric will be the same as result_alpha.
* result_unit - unit of the result value. In case of micro notation just use regular 'u' instead.
* ligand_conc - ligand concentration and units e.g. 10 uM.
* time_step - time after which assay was recordded e.g. 10 min.
* comments - any other relevant information e.g. conditions, substrate concentrations etc.
* (R) creation_date - date of the assay.
* study_id - in-house project identifier associated with the assay.
* (R) data_source - origin the records e.g. collaborator, vendor names, in-house.

## Setup
* Setup as a notebook type protocol and link to a form on Browser.

