# COVID-19 Vaccination Analysis in Germany

## Authors

* Felix Obermaier
* Lukas Seibold

## Project Description

This project was created as part of the StatProg2 course. The aim of the analysis is to investigate COVID-19 vaccination trends in Germany and explore possible relationships between vaccination coverage, mortality, and intensive care unit (ICU) occupancy.

## Data Source

The data originates from the *Our World in Data (OWID) COVID-19 Dataset*. For this project, the dataset was filtered to include observations for Germany only.

## Research Questions

1. How did vaccination coverage in Germany develop during the COVID-19 pandemic?
2. Are higher vaccination rates associated with lower COVID-19 mortality in Germany?
3. Are higher vaccination rates associated with lower numbers of ICU patients in Germany?

## Website

The final project results are presented through a GitHub-hosted Quarto website containing visualizations, statistical analyses, and interpretations of the findings.



## Practical #10 — one improvement

**Before:** a bare default line chart — raw axis labels (`date`,
`people_fully_vaccinated_per_hundred`), no title, no context.

**After:** added a title, a subtitle that states the finding, clean axis
labels, and `theme_minimal()`.

What changed and why: the default plot showed the data but not the message.
The subtitle now states the finding directly ("a steep rise in 2021, then a
plateau around 76%"), so a reader can take the conclusion from the figure
alone instead of having to read the curve themselves.