****

Data and R code accompanying:

<b>Add title</b>

Authors: [Dominique G. Maucieri](https://dominiquemaucieri.com), [Samuel Starko](https://samstarko.wordpress.com/) and [Julia K. Baum](https://www.juliakbaum.org)

****


[Scripts Folder](scripts/)

* [Alpha_Diversity.Rmd](scripts/Alpha_Diversity.Rmd): Script used to:
	- Conduct alpha diversity analyses
	- Figures 4a-c and S2-6
	- Table 1, S1, and S3-4
	- [Alpha_Diversity.html](scripts/Alpha_Diversity.html): HTML file containing the output of [Alpha_Diversity.Rmd](scripts/Alpha_Diversity.Rmd) 

* [Beta_Diversity.Rmd](scripts/Beta_Diversity.Rmd): Script used to:
	- Conduct beta diversity analyses
	- Figure 3, 4d and S7
	- [Beta_Diversity.html](scripts/Beta_Diversity.html): HTML file containing the output of [Beta_Diversity.Rmd](scripts/Beta_Diversity.Rmd)


[Data Folder](data/)

* [Alpha_Diversity.RData](data/Alpha_Diversity.RData) contains:

	- Alpha_Diversity_df.csv: Raw coral cover data from Kiritimati island from sites used in alpha diversity analyses
		* ```UniqueID```: Unique identification for each quadrat at each site in each year sampled
		* ```Year```: Year that the data was collected
		* ```Site```: Site number
		* ```Quadrat```: Quadrat ID
		* ```SiteYear```: Site year combination ID
		* ```HD_Cat```: Estimate of local human disturbance at each site as a categorical variable
		* ```HD_Cont```: Estimate of local human disturbance at each site as a continuous variable
		* ```NPP```: Max net primary productivity at each site (mg C m^-2 day^-1)
		* ```MHW```: If the sampling season was before, during or after the El Niño event
		* ```Acropora.spp```:  Coral cover (%) for Acropora spp
		* ```Astrea.spp```:  Coral cover (%) for Astrea spp
		* ```Astreopora.spp```:  Coral cover (%) for Astreopora spp
		* ```Cladiella.spp```:  Coral cover (%) for Cladiella spp
		* ```Dipsastraea.spp```:  Coral cover (%) for Dipsastraea spp
		* ```Favites.spp```:  Coral cover (%) for Favites spp
		* ```Fungiidae```:  Coral cover (%) for Fungiidae
		* ```Gardineroseris.planulata```:  Coral cover (%) for Gardineroseris planulata
		* ```Goniastrea.edwardsi```:  Coral cover (%) for Goniastrea edwardsi
		* ```Goniastrea.stelligera```:  Coral cover (%) for Goniastrea stelligera
		* ```Hydnophora.exesa```:  Coral cover (%) for Hydnophora exesa
		* ```Hydnophora.microconos```:  Coral cover (%) for Hydnophora microconos
		* ```Leptastrea.spp```:  Coral cover (%) for Leptastrea spp
		* ```Leptoseris.myceteroides```:  Coral cover (%) for Leptoseris myceteroides
		* ```Lobophyllia.spp```:  Coral cover (%) for Lobophyllia spp 
		* ```Lobophytum.spp```:  Coral cover (%) for Lobophytum spp
		* ```Montipora.spp```:  Coral cover (%) for Montipora spp
		* ```Pavona.duerdeni```:  Coral cover (%) for Pavona duerdeni
		* ```Pavona.varians```:  Coral cover (%) for Pavona varians
		* ```Platygyra.spp```:  Coral cover (%) for Platygyra spp
		* ```Pocillopora.spp```:  Coral cover (%) for Pocillopora spp 
		* ```Porites.spp```:  Coral cover (%) for Porites spp
		* ```Psammocora.profundacella```:  Coral cover (%) for Psammocora profundacella
		* ```Sarcophyton.spp```:  Coral cover (%) for Sarcophyton spp
		* ```Sinularia.spp```:  Coral cover (%) for Sinularia spp
		* ```Turbinaria.spp```:  Coral cover (%) for Turbinaria spp
		* ```Not.Coral```:  Cover (%) for all non-coral organisms and benthic substrates


* [Beta_Diversity.RData](data/Beta_Diversity.RData) contains:

	- Beta_Diversity_df.csv: Raw coral cover data from Kiritimati island from sites used in beta diversity analyses
		* ```UniqueID```: Unique identification for each quadrat at each site in each year sampled
		* ```Year```: Year that the data was collected
		* ```Site```: Site number
		* ```Quadrat```: Quadrat ID
		* ```SiteYear```: Site year combination ID
		* ```HD_Cat```: Estimate of local human disturbance at each site as a categorical variable
		* ```HD_Cont```: Estimate of local human disturbance at each site as a continuous variable
		* ```NPP```: Max net primary productivity at each site (mg C m^-2 day^-1)
		* ```MHW```: If the sampling season was before, during or after the El Niño event
		* ```Acropora.spp```:  Coral cover (%) for Acropora spp
		* ```Astrea.spp```:  Coral cover (%) for Astrea spp
		* ```Astreopora.spp```:  Coral cover (%) for Astreopora spp
		* ```Cladiella.spp```:  Coral cover (%) for Cladiella spp
		* ```Dipsastraea.spp```:  Coral cover (%) for Dipsastraea spp
		* ```Favites.spp```:  Coral cover (%) for Favites spp
		* ```Fungiidae```:  Coral cover (%) for Fungiidae
		* ```Gardineroseris.planulata```:  Coral cover (%) for Gardineroseris planulata
		* ```Goniastrea.edwardsi```:  Coral cover (%) for Goniastrea edwardsi
		* ```Goniastrea.stelligera```:  Coral cover (%) for Goniastrea stelligera
		* ```Hydnophora.exesa```:  Coral cover (%) for Hydnophora exesa
		* ```Hydnophora.microconos```:  Coral cover (%) for Hydnophora microconos
		* ```Leptastrea.spp```:  Coral cover (%) for Leptastrea spp
		* ```Leptoseris.myceteroides```:  Coral cover (%) for Leptoseris myceteroides
		* ```Lobophyllia.spp```:  Coral cover (%) for Lobophyllia spp 
		* ```Lobophytum.spp```:  Coral cover (%) for Lobophytum spp
		* ```Montipora.spp```:  Coral cover (%) for Montipora spp
		* ```Pavona.duerdeni```:  Coral cover (%) for Pavona duerdeni
		* ```Pavona.varians```:  Coral cover (%) for Pavona varians
		* ```Platygyra.spp```:  Coral cover (%) for Platygyra spp
		* ```Pocillopora.spp```:  Coral cover (%) for Pocillopora spp 
		* ```Porites.spp```:  Coral cover (%) for Porites spp
		* ```Psammocora.profundacella```:  Coral cover (%) for Psammocora profundacella
		* ```Sarcophyton.spp```:  Coral cover (%) for Sarcophyton spp
		* ```Sinularia.spp```:  Coral cover (%) for Sinularia spp

	- Least_Cost_Distance.csv: Least cost distances between sites without crossing land

		* ```start.site```: Start site where distance is measured from
		* ```end.site```: End site where the distance is measured to	
		* ```cost```: Cost associated with the distance between sites
		* ```distance_km``` The distance in km between the sites
		* ```site_comb``` The site combination ID

	- quadrats_sampled.csv: Data frame containing all possible quadrats that were randomly sampled to produce the final Beta_Diversity_df.csv
		
		* ```UniqueID```: Unique identification for each quadrat at each site in each year sampled
		* ```Year```: Year that the data was collected
		* ```Site```: Site number
		* ```Quadrat```: Quadrat ID
		* ```SiteYear```: Site year combination ID
		* ```MHW```: If the sampling season was before, during or after the El Niño event
		* ```MHW_Site```: MHW Site combination ID

	- siteyear_factor: a factor containing the possible site year combination IDs that contain more than 25 quadrats each

	
[Figures and Tables Folder](figures_tables/)

* [Figure 2](figures_tables/Figure_2.jpeg)
* [Figure 3](figures_tables/Figure_3.jpeg)
* [Figure 4a](figures_tables/Figure_4a.jpeg)
* [Figure 4b](figures_tables/Figure_4b.jpeg)
* [Figure 4c](figures_tables/Figure_4c.jpeg)
* [Figure 4d](figures_tables/Figure_4d.jpeg)
* [Figure S2](figures_tables/Figure_S2.jpeg)
* [Figure S3](figures_tables/Figure_S3.jpeg)
* [Figure S4](figures_tables/Figure_S4.jpeg)
* [Figure S5](figures_tables/Figure_S5.jpeg)
* [Figure S6](figures_tables/Figure_S6.jpeg)
* [Figure S7](figures_tables/Figure_S7.jpeg)
* [Table S1](figures_tables/Table_S1.xlsx)
* [Table S4](figures_tables/Table_S4.xlsx)


