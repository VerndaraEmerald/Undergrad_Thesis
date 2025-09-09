# Undergrad Thesis
## Summary
Community colleges are offering BSNs in some states, but are they effective in responding to local labor market shortages?

## Data
The data is drawn from IPEDS, 2002-2023, for all tertiary education in the United States. The c####_a files features the number of graduates per year, per school, disaggregated by race, award level, and CIP code. The hd#### files give the institutional characteristics, which is useful for identifying community colleges and creating 25-mile geographic clusters using addresses. We employ R to clean, filter, and merge the data.

## Methodology
We first aim to reproduce a previous model suggested in *Local Influences of Community College Baccalaureate Legislation on Nursing and Teaching Degree Production in Florida* by Nathan Daun-Barnett and Silas Escalante. From there, we use Bacon-Goodman decomposition to assess the potential bias in their two-way fixed effects model, and conclude with a Santana-Callaway staggered difference-in-difference.

# Acknowledgments
This project would not be done without the support of many of my faculty at CSULB, namely my advisor, Dr. Olga Korosteleva. I would additionally like to thank the University Honors Program for their support throughout my 4 years, highlighting Dr. Lauren Heidbrink and Dr. Oliver Wang for supporting me in the first 2 semesters of the thesis.

Furthermore, this project would never have unfolded without the assistance of wider economics community. First, I'd like to thank the American Economic Association and Howard University for hosting me and my cohort at AEASP 2025, in particular highlighting Dr. Durronjae Boothe at Howard for being the first to suggest the staggered difference-in-difference model. I would also like to thank the Academic Economics Discord for supporting me in my journey as someone curious in economics, especially (aliased names) Rae, Kenmore, and Heisenberg for listening to my spiels about community college bachelor's degrees and suggesting the models and papers that comprise this project.