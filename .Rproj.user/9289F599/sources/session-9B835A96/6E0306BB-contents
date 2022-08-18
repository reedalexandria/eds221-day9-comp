#---Practicing reprex---#

library(tidyverse)
library(palmerpenguins)

### Not a reprex
penguins |>
  select(species, body_mass_g, flipper_length_mm, year) |>
  filter(species == "Chinstrap") |>
  str_to_lower(species) |>
  group_by(island) |>
  summarize(mean(body_mass_g, na.rm = TRUE),
            mean(filpper_length_mm, na.rm = TRUE))

### A reprex
library(tidyverse)

warpbreaks |>
  str_to_lower(wool) 

### Fixing
library(tidyverse)

warpbreaks |>
  mutate(wool = str_to_lower(wool))

### A reprex with a synthesize data frame
library(tidyverse)

warp <- tribble(~wool,
        "A",
        "A",
        "A")

warp |>
  mutate(wool = str_to_lower(wool))




