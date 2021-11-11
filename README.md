# Drug Study on Mice
This program is used to evaluate the efficacy of different drugs on tumors in rats.

The program reads 2 CSV files containing metadata on the mice and the data recorded from the study. The `merge` command from the pandas module is used to merge the two sets of data together. It is then sent through several commands to find duplicate entries for mice and remove them.

The data is then summarized by drug regimen determining:
- Tumor Vol. Mean(mm3)
- Tumor Vol. Median(mm3)
- Tumor Vol. Variance
- Tumor Vol. Std. Deviation
- Tumor Vol. SEM

Several plots are then produced from the data using both plotly and pandas to display different programming methods.
