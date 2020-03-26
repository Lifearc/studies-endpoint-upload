# Setup and usage description for Studies protocol to upload endpoint assay data:squirrel:

## :floppy_disk:Downloads
* [Template](template.xlsx)
* [Example submission](example_submission.xlsx)

## :zap: Usage
* Data submission must be in .xlsx or .csv formats.
* :one: Use the template file to fill in your submission. Take care to preserve the column order.
* :two: Create new experiment in Endpoint Data protocol, type in a name and a description.
* :three: In the 'Data Upload' section click on '+' to upload the data.
* :warning:Check if your browser is not blocking the pop up for (applies for first time users of the protocol).
<br/><br/>
![alt text](https://www.howtogeek.com/wp-content/uploads/2019/04/x2019-04-17_12h32_07-2.png.pagespeed.gp+jp+jw+pj+ws+js+rj+rp+rw+ri+cp+md.ic.TOnKYPJvpu.png)
* :four: Review if data is parsed correctly and approve.
* Upload any other relevant associated files or notes.
* :five: Complete the experiment in Studies once finished with the submission to make it available to other Browser forms.
* :warning: Different experimental runs must be submitted as separate Studies experiments instead of mashing submission up into one.
* You can delete the submission by deleting the associated document. The data associated will get removed from the system too.

## :bulb: Template column description
:heavy_exclamation_mark: marks required columns to fill in for your submission.
* :heavy_exclamation_mark: sample_id - an identifier for a sample tested e.g. compound ID.
* :heavy_exclamation_mark: sample_batch - sample batch number. You should always record batch ID for a compound or biological entity. The only exception can be sequence expressions and can be recorded as 0.
* eln_id - ELN ID to link experiment with ELN records. Should be always applicable for in-house experiments.
* test_id - a test ID of an assay. Used to distinguish between different repeated runs, especially if done on the same date.
* study_type - type of the study assay is associated with e.g. KINASE or ADME or PROTEIN-PROTEIN INTERACTION.
* :heavy_exclamation_mark: target - the name of the target. In case of ADME assay recorded as ADME, if it's a cell line - record it here
* gene - if target is a protein or protein complex please specify a respective gene(s), separated by a dash e.g. JAK2-TYK2.
* organism - specify target species in Latin.
* cell_line - if cell based assay specify cell line used. In case target is a cell line you end up recording cell line twice. You can refer to ATCC for offical names of cell lines.
* :heavy_exclamation_mark: assay_name - name of the assay or protocol.
* :heavy_exclamation_mark: assay_type - type/category of the assay.
* :heavy_exclamation_mark: result_type - result type e.g. IC50, Primary Screen.
* result_modifier - modifier describing numerical result e.g. '>' or '='
* result_numeric - numerical value of the assay result.
* :heavy_exclamation_mark: result_alpha - full result value. This should be a combination of result_modifier and result_numeric. In case a modifier is absent result_numeric will be the same as result_alpha.
* result_unit - unit of the result value. In case of micro notation just use regular 'u' instead.
* ligand_conc - ligand concentration and units e.g. 10 uM.
* time_step - time after which assay was recordded e.g. 10 min.
* comments - any other relevant information e.g. conditions, substrate concentrations etc.
* :heavy_exclamation_mark: creation_date - date of the assay.
* study_id - in-house project identifier associated with the assay.
* :heavy_exclamation_mark: data_source - origin of the records e.g. collaborator, vendor names, in-house.

## :hammer: Setup
* Setup as a notebook type protocol and link to a form on Browser.

