# test
library(RPiR)
available_lectures()
available_practicals()
run_practical("practical1-1")
devtools::install_github("IBAHCM/RPiR", build_vignettes = TRUE, force = TRUE)
