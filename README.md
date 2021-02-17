# Shiny SIR-Vaccine

This is a Shiny app to illustrate the SIR-Vaccine model.

The SIR (Susceptible-Infected-Removed) model consists of a system of three coupled non-linear ordinary differential equations. 
A vaccine sends some Susceptible directly to the Recovered (immune) state. 
Shiny apps help us create an interactive web application for this model.

 
To run this App, the following packages need to be installed:

```{r}
library("shiny")
library("deSolve")
library("cowplot")
library("ggplot2")
library("tidyverse")
library("ggrepel")
library("shinydashboard")
```
