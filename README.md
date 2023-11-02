# Cleaning-Data
A portfolio showing the various step by step process in working a dataset to the point it is clean and ready for analysis.

The dataset has columns 're', 'le' and 'be' an abbreviation for right ear, left ear and both ear.

The values in the 're' and 'le' columns range from 'normal', 'mild hearing loss', 'morderate hearing loss' to 'severe hearing loss' representing the state of hearing of the patient.

The 'be' column has no values and is to be computed from the 're' and 'le' column, it should state 'normal' if both 're' and 'le' says normal, 'mild' if both 're' and 'le' are 'mild hearing loss', moderate and severe if both 're' and 'le' columns both state 'moderate hearing loss' and 'severe hearing loss' respectively, any values outside of those would be represented as 'other'.

The objective is to populate the 'be' column after which the dataset can be analysed to give a comprehensive report on the state of the patients hearing.
