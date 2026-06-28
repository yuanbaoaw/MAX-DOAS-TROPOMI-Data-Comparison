# MAX-DOAS-TROPOMI-Data-Comparison
Code for after finishing retrieval. Include merge the profile, use the TROPOMI ak to smooth the MAX-DOAS profile data. The smoothed data is using to compare.

<merged_profile_myriad.py>

For MAX-DOAS. When finishing the retrieval, put merged_profile_myriad.py at the selected year. The file named 'all_profile_{Year}.csv', 'all_profile_{Year}.pck' should be generated.

<DATAPROCESSING_ALLINONE.ipynb>

For both MAX-DOAS and TROPOMI. After downlading the retrieval data, just change the {Year} at the front to generate the smoothed data. The smoothed data is ready to compare with TROPOMI dataset.
