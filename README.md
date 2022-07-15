# Lost In Starvation
Image Analysis and Simulation codes for thesis

Thesis Abstract:
Heterotrophic marine bacteria navigate a heterogeneous landscape of resources. Bacterial populations cycle through periods of feasting when attached to nutrient particles and periods of famine when foraging between hotspots; thus, bacterial physiological states and ecological processes are intertwined. The stress response to nutrient limitation appears within three hours, while the encounter time to new particles has been estimated to happen on the scale of days. Therefore, it is unclear how the phenotypic changes undergone by bacteria during starvation affect their ability to search for and acquire nutrients. Here, we quantified the physiological responses of the marine heterotroph \textit{Vibrio coralliilyticus} to carbon and nitrogen starvation and its subsequent success at foraging in a landscape of resource particles. We compare the foraging success of different bacterial populations in terms of the minimum number of particles needed for ten percent of such a population to encounter any particle. We parametrize a model of bacterial foraging during starvation superposing multiple Poisson processes using measurements of viability, motility, attachment, and renewed growth observed for \textit{Vibrio coralliilyticus} over several days of carbon and nitrogen limitation. We find that motility loss, bacterial persistence, and reductive cellular division are key behaviours determining foraging success. While motility loss increases the number of particles required for successful foraging in a population, bacterial persistence relaxes that constraint. Heightened reductive division accelerates the speed at which the first ten percent of the initial bacterial population achieves a particle encounter. This work provides a quantitative estimate of the influence of nutrient-limited phenotypes on bacterial foraging success in a marine environment.


Code available here:
- Attachement: quantification of chitin bead size and number of attached bacteria
      Main file: Bead_quantification_elise_v3.mlx
      Example Input - Z-stack from ImageXpress: 21h 7day 45_B07_s15.tif (21h incubation in chitin beads with bacteria starved 7 days)
      Example Output - Table written as a result of the pipeline: 20210514Out.csv 
- Motility: get trajectories out of microscopy movies
      Main file: Trajectory_quantification_v6.ipynb
      Based on the trackpy package: http://soft-matter.github.io/trackpy/v0.5.0/
- Foraging Simulation: simulate bacterial trajectories
