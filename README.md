# Birth Preparedness and Complication Readiness (BPCR) Analysis — Hargeisa

## Project Overview
An Excel-based descriptive analysis of Birth Preparedness and Complication Readiness (BPCR) among women represented in a Hargeisa dataset. Topics include demographic characteristics, antenatal care (ANC), BPCR health education, knowledge of maternal danger signs, place of birth, and reported preparedness practices.

## Tool
- Microsoft Excel

## Dataset and Source
A closely matching peer-reviewed study is available: Ahmed et al. (2024), [Birth preparedness and complication readiness among recently delivered women in Hargeisa town, Somaliland](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0302168). The study was community-based, conducted in September 2022, and analyzed 300 women. It used a pre-structured questionnaire adapted from JHPIEGO BPCR tools and defined good BPCR knowledge as mentioning at least three of five components; preparedness required preparation for at least three of five components.

The similarity in study setting and sample size suggests this paper may be the source or a close match for the workbook. The repository does not currently document the exact original file or prove that the workbook contains the same records, so treat this source match as probable rather than confirmed until the questionnaire/data provenance is checked.

## Published Study Results (Reference for Comparison)
In the published study, 115/300 women (38.3%) had good BPCR knowledge and 75/300 (25.0%) were prepared for birth and its complications. The paper also reports 191 women with ANC during the last pregnancy among 248 women with that response available (77.0%); this is not the same denominator as all 300 participants.

These are the published study's figures, **not yet independently reproduced from this repository's workbook**. The previous workbook summary stated that only 2/300 (0.7%) were prepared. That conflicts with the published paper if the workbook represents the same study. Do not present 0.7% as a verified result until the Excel scoring formula, component fields, missing responses, and denominator have been audited and reconciled.

## Analysis Workflow
- Validate records and variable coding
- Calculate frequency distributions and descriptive summaries
- Summarize knowledge of pregnancy, labor, and postpartum danger signs
- Reproduce the BPCR knowledge and preparedness classifications using the source definitions where applicable
- Check missing responses and denominator consistency

## Scoring and Missing Values
For comparison with the published study, the source paper defines:
- Good BPCR knowledge: at least three of five BPCR components mentioned
- Prepared for birth and complications: at least three of five preparedness components completed

Use these definitions only if the workbook's provenance confirms that it corresponds to the same study and variables. Document each item, its coding, how the score was calculated, and how incomplete responses were handled. Do not call a classification validated without supporting evidence.

## Limitations
- Confirm whether the workbook is the dataset used in the cited article.
- Check missing values separately from valid No responses.
- Report the denominator for every percentage.
- Findings are descriptive and do not establish causality.
- Before sharing the workbook publicly, check for direct identifiers or sensitive individual-level information.

## Project Files
- [Dashboard preview](<./Dashboard2%20.png>)
- [Excel data-cleaning workbook](<./Data%20Cleaning%20BPCR%20.xlsx>)

## Project Purpose
This project demonstrates Excel skills in maternal-health data cleaning, descriptive analysis, scoring transparency, and responsible reporting of missing data.

## Reference
Ahmed AM, Ahmed MA, Hassen M. (2024). [Birth preparedness and complication readiness among recently delivered women in Hargeisa town, Somaliland: A community-based cross-sectional study](https://doi.org/10.1371/journal.pone.0302168). PLOS ONE, 19(4), e0302168.

## Additional Verification Note
The repository's workbook summary and the published Hargeisa study do not currently agree on the prepared-for-birth count: the summary says 2/300 (0.7%), while the paper reports 75/300 (25%). The paper also reports 191 women with ANC during their last pregnancy among 248 women who had ever attended ANC; this should not be confused with 191/300. Confirm that this workbook is the study's dataset and reproduce the published scoring definition before claiming the workbook results are verified.
