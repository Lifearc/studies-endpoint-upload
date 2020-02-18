# Setup and usage description for Studies protocol to uplaod endpoint assay data

## Usage
* Maintain colunmn order as in the template.xlsx file.
* Create new experiment in LifeArc_endpoint_data protocol, record ELN ID in the description box.
* Check if your browser is not blocking pop up for processing script selection.
* Check if data is parsed correctly and approve.
* Upload any other relevant associated files.
* Complete experiment once finished with submission.

## Template column description
(R) marks required columns to fill in.
* (R) sample_id - an identifier for a sample tested e.g. compound ID.
* sample_batch - sample batch number. You should always not batch ID for a compound or biological entity.
* test_id - a test ID of an assay.
* study_type - type of the study assay is associated with e.g. KINASE or ADME or PROTEIN-PROTEIN INTERACTION.
* target - the name of the target. In case of ADME assay leave it empty.
* gene - if target is a protein or protein complex please specify a respective gene.
* organism - specify target species.
* cell_line - if cell based assay specify cell line used.
* (R) assay_name - name of the assay or protocol.
* assay_type - type of the assay
* (R) result_type - result type e.g. IC50, Primary Screen.
* result_modifier - modifier describing numerical result.
* result_numeric - numerical value of the assay result.
* (R) result_alpha - full result value.
* result_unit - unit of the result value.
* comments - any other relevant information e.g. conditions, concentrations etc.
* (R) creation_date - date of the assay.
* study_id - in-house project identifier associated with the assay.
* data_source - origin the records e.g. collaborator, vendor names. If in-house leave empty or record as LifeArc.

## Examples
