 ## author information: 
        Author: Haley Curtis
        Position: 2nd-year PhD student in Biology at Penn State.
        Research interests: bumble bee foraging ecology and related stressors.
 ## a brief description of how the data were collected:
        The data were collected in the Summer of 2025. Pollen balls were collected from 12 bumble bees and 
        12 honey bees at 3 different habitat types at 5 different sampling periods throughout the summer. Plant content in the pollen was obtained
        using DNA metabarcoding. P:L content in the pollen was obtained using Bradford and Vanillin assays.
 ## file names and full descriptions of column names within each file (with measurement units and notes indicating primary or foreign keys if relevant)
        Data_Raw Files:
              data_metabarcoding.csv
                  bee_id (text - foreign key)
                      the bee on which the pollen sample was collected (genus_site_timeperiod)
                  proportion (float)
                      proportion of plant in pollen sample
                  plant_genus (text)
                      plant genus found within the pollen sample
              data_pl.csv
                  bee_id (text - foreign key)
                      the bee on which the pollen sample was collected (genus_site_timeperiod)
                  date (date)
                      the date on which the pollen was collected
                  bee_genus (text)
                      the genus of the bee
                  bee_caste (text)
                      the caste of the bee
                  site (text)
                      the site at which the bee was collected
                  site_type (text)
                      the habitat type at which the bee was collected
                  sampling_period (float)
                      the sampling period at which the bee was collected
                  concentration_lipid (float)
                      the lipid concentration of the pollen measured in ug/mg.
                  concentration_protein (float)
                      the protein concentration of the pollen measured in ug/mg.
                  concentration_pl (float)
                      the protein-to-lipid ratio concentration of the pollen (protein/lipid).