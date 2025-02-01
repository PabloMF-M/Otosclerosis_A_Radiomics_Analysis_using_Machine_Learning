
DATABASES
---------

In this project, several databases have been used, which are detailed below. Some listed databases have not been included in this repository for privacy and anonymization reasons.


A. Clinical data
----------------

- 0_Otosclerosis_clinical_data.xlsx: raw clinical data collected.

- 1_df_clinical_data_anonymized.csv/xlsx: clinical data collected after anonymize patient ID and dates.

- 2_df_clinical_data_cleaned.csv/feather/xlsx: anonymized and cleaned clinical data.



B. Radiomic features
--------------------


B.1. Fist radiomic features extraction
--------------------------------------

- 3_1_df_radiomics_STAPES_dummy_features.csv: dummy extraction to adjust bin width and params file for STAPES segmentations.

- 3_2_df_radiomics_AF_dummy_features.csv: dummy extraction to adjust bin width and params file for AF segmentations.

- 3_3_df_radiomics_OW_dummy_features.csv: dummy extraction to adjust bin width and params file for OW segmentations.



B.2. Final radiomic features extraction
---------------------------------------

- 4_1_df_radiomics_STAPES_tuned_final_features.csv/xlsx: final radiomic features for STAPES segmentations.

- 4_2_df_radiomics_AF_tuned_final_features.csv/xlsx: final radiomic features for AF segmentations.

- 4_3_df_radiomics_OW_tuned_final_features.csv/xlsx: final radiomic features for OW segmentations.



B.3. Cleaned radiomic features
------------------------------

- 5_1_df_radiomics_STAPES_tuned_final_features_cleaned.csv/feather/xlsx: final STAPES radiomic features cleaned.

- 5_2_df_radiomics_AF_tuned_final_features_cleaned.csv/feather/xlsx: final AF radiomic features cleaned.

- 5_3_df_radiomics_OW_tuned_final_features_cleaned.csv/feather/xlsx: final OW radiomic features cleaned.



B.4. Cleaned and merge clinical data and radiomic features
----------------------------------------------------------

- 6_df_radiomics_&_clinical.csv/xlsx/feather: database with cleaned radiomic and clinical data.

