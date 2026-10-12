# Distraction Levels and Reaction Times

A linear mixed model analysis of how distraction levels affect reaction times.

Twenty-eight participants took a reaction-time test four times under each of four conditions:

- standing in a distraction-free space
- standing in a bustling area
- walking in a distraction-free space
- walking briskly in a bustling area

The model allows error variance to differ by distraction level. A secondary analysis looks at noise level and how it interacts with the distraction conditions.

## Contents

| Path | Description |
| --- | --- |
| `data/reaction_time_distraction_data.csv` | The study data |
| `eda/eda.qmd` | Data cleaning and exploratory analysis |
| `analysis/reaction-time-analysis.qmd` | Linear mixed model analysis |
| `report/final-report.docx` | Final written report |

The Quarto files read the data through a relative path. Render them from inside their own folders.
