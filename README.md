# proyecto-final-
la precipitacion 

  ggplot(Pp_pisco, aes(fecha, precipitacion)) + 
    geom_line() +
    geom_smooth(span = 0.4)
  names(Pp_pisco)
