if (.Platform$OS.type == 'windows') Sys.setlocale(, 'Chinese')

.CUSTOM_LIB = "~/Tools/R/R_Library"
.libPaths(c(.CUSTOM_LIB, .libPaths()))
message("Using library: ", .libPaths()[1], "as main library")

if(!require(pacman)){
  install.packages("pacman", dependencies = TRUE)
}
library(pacman)
