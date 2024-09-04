# Description of datafiles
*fig_1_body_weight.csv*
Each row is a different mouse. Columns with animal characteristics (ID, sex, and group) are followed by 9 columns (“week_0” through “week_8”), each of which contains the average body weight (in grams) for that mouse.

*fig_2_body_composition.csv*
Each row is a different mouse. Columns with animal characteristics (ID, sex, and group) are followed by columns with each mouse’s echoMRI measurements of fat mass and lean mass  at baseline (“fat_baseline” and “lean_baseline”), and at the experiment’s conclusion (“fat_end” and “lean_end”). Finally, there are two columns for the change in body composition between experiment start and end (“change_in_fat” and “change_in_lean”). All numbers are in grams.

*fig_3_food_intake.csv*
Each row is a different mouse. Columns with animal characteristics (ID, sex, and group) are followed by 9 columns (“week_0” through “week_8”), each of which contains the average daily food intake, in grams, for that mouse. The last two columns have the average daily food intake in weeks during which the IPR group was on PR diet (weeks 1,3, 5, and 7) and on weeks when the IPR group was on NR diet (weeks 2,4,6, and 8). 

There are 3 cells that contain estimated intakes. Cell F16 (MPX301, NR, week 2) was estimated by averaging this mouse’s intake in all other weeks, as was cell H61 (IPR18, PR, week 4) with the exception that this mouse’s baseline intake was not included as it was on a different diet. Lastly, cell D31 (MPX306, PR, baseline) was estimated by averaging the baseline intakes of all other male mice.

*fig_4_protein_intake.csv*
Each row is a different mouse. Columns with animal characteristics (ID, sex, and group) are followed by 9 columns (“week_0” through “week_8”), each of which contains the average protein intake in grams consumed by that particular mouse on that week. The final columns have the average protein intake for each mouse on weeks when the IPR group was on PR diet (weeks 1,3, 5, and 7) and on weeks when the IPR group was on NR diet (weeks 2,4,6, and 8).

*fig_5_ghrelin.csv*
Each row is a different mouse. Columns with animal characteristics (ID, sex, and group) are followed by the time in which plasma was collected (“dark_onset” or “light_onset”), and the final column shows the concentration of ghrelin (pg/ml). 

Note that the value in cell E17 (MPX325, NR in dark onset) was excluded from statistical analyses because it is an outlier (2 standard deviations above the group mean).
