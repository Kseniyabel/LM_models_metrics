## Comparison of model quality metrics for predicting the next word in medical texts in the DoctorType project.

To compare the model quality metrics and demonstrate their work, stories were selected according to the profile “Therapy and internal diseases”.
There are 74 complete medical records in total, the test sample made up 10% of all data.
The test sample includes inpatient open access records from two different sources, as well as outpatient medical records collected by the team.
During the preprocessing of the data, all technical symbols, numbers, punctuation marks were removed from the text, and the text was reduced to lowercase.
The dictionary size for the STM and transformer decoder models was 20413 tokens, for ruGPT3 - 50264.
The length of the input sequence in all models was 64 tokens.
