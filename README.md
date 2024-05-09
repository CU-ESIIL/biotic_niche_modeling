[![DOI](https://zenodo.org/badge/748406149.svg)](https://zenodo.org/doi/10.5281/zenodo.11167964)

# Postdoc OASIS
This is the central hub for information pertaining to ESIIL Postdocs

# Robert J Ramos

Welcome to the Rob Ramos repository, part of the Environmental Data Science Innovation and Inclusion Lab (ESIIL). This repository serves as the central hub for our research at ESIIL, hosting the project description, proposals, bio, codebase, and more.

## The Project

My proposed research would expand on work understanding the spatial patterns and niche characteristics of Arbuscular Mycorrhizal (AM) fungi. Recent interest in niche modeling of AM fungi simultaneously with their plant hosts shows there is great potental in extending niche modeling techniques to better understand species interactions (Kivlin et. al., 2023, “Specificity and environmental niche breadth of mycorrhizal fungi may predict their response to global change.” ESA 2023 Annual Meeting, Portland, OR, United States). Current efforts rely heavily on ribosomal small subunit (SSU) or internal transcribed spacer (ITS) sequences which have been shown to have poor ability to distinguish AM fungi at the genus level (Delavaux et. al., 2021, “Utility of large subunit for environmental sequencing of arbuscular mycorrhizal fungi: a new reference database and pipeline.” New Phytol, 229:6). I propose a niche modeling effort which will utilize data from curated studies which sequenced ribosomal large subunit (LSU) genes. Additionally I would utilize explicitly phylogenetic analysis to look for evidence of co-evolution or evolutionary conservatism in host-symbiont relationships.

## Project Proposal

My proposed research will utilize both ribosomal LSU amplicon sequencing and plant occurrence data from Global Biodiversity Information Facility (GBIF). Much of the AM fungal amplicon data available publicly utilize the ribosomal SSU, or ITS regions. These regions have poor efficacy resolving identification to the genus level (Delavaux et. al., 2021, “Utility of large subunit for environmental sequencing of arbuscular mycorrhizal fungi: a new reference database and pipeline.” New Phytol, 229:6). Many recent field studies have utilized the LSU (Cheeke, et. al., 2019, “Sensitivity to AMF species is greater in late-successional than early-successional native or nonnative grassland plants”. Ecology, 100:12) (Wang et al., 2022, “Microbial Mediators of Plant Community Response to Long-Term N and P Fertilization: Evidence of a Role of Plant Responsiveness to Mycorrhizal Fungi.” Global Change Biology, 28:8). Collating this data together creates an opportunity to better resolve the niche space of AM fungi then relying on SSU and ITS sequences downloaded from National Center for Biotechnology Information (NCBI) Genebank. GlobalAMFungi exists as a large database of plant AM fungal feedback studies (Větrovský, et al. (2023), GlobalAMFungi: a global database of arbuscular mycorrhizal fungal occurrences from high-throughput sequencing metabarcoding studies. New Phytol, 240: 2151-2163). This database of 8464 samples from across 100 studies would be a good starting point for collating a more specific set of field studies that collected AM Fungal environmental sequences. Collected a single dataset of curated AM fungal LSU environmental sequences will represent a useful and novel data product in itself. 

In addition to AM fungal presences derived from LSU amplicon sequencing, I plan to utilize host plant presence data from the GBIF database. The GBIF database is one of the largest species occurrence databases publicly available, and is actively pursuing the goal of being a resource for species distribution modeling (Anderson et. al., 2016, “Are species occurrence data in global online repositories fit for modeling species distributions? The case of the Global Biodiversity Information Facility (GBIF)”. GBIF Secretariat). Spatial bias in occurrence data is a documented issue in GBIF data, with the United States being one of the over-represented regions in the database (Rocchini et. al., 2023. “A quixotic view of spatial bias in modelling the distribution of species and their diversity”. Npj Biodiversity, 2:1). For this reason and because of the high number of AM Fungal studies conducted with North American AM fungal species, I propose to limit the geographic extent of my modeling efforts to the contiguous United States (Delavaux et. al., 2017, “Beyond nutrients: A meta-analysis of the diverse effects of arbuscular mycorrhizal fungi on plants and soils.” Ecology, 98:8).

## Collaborators and Co-Authors 

- **[James D. Bever](https://eeb.ku.edu/people/james-bever)**: a foundation distinquished professor in the department of Ecology and Evolutionary Biology of KU, research interests include: population and community ecology, mutualisms, mycorrhizae, pathogens, and microbiome feedback.
- **[Jorge Soberón](https://eeb.ku.edu/people/jorge-soberon)**: a distinguished professor in the department of Ecology and Evolutionary Biology of KU, works mostly on the theoretical aspects of niche modeling and geographic patterns of biodiversity.

## Code Repository

- **[Analysis Code](https://github.com/CU-ESIIL/biotic_niche_modeling/tree/main/analysis)**: Scripts for data analysis, statistical modeling, etc.
- **[Data Processing](https://github.com/CU-ESIIL/biotic_niche_modeling/tree/main/processing)**: Scripts for cleaning, merging, and managing datasets.
- **[Visualization](https://github.com/CU-ESIIL/biotic_niche_modeling/tree/main/visualization)**: Code for creating figures, charts, and interactive visualizations.

## Meeting Notes and Agendas

When you meet with your advisor, collaborators, or a team, you should take notes here. 

## Contributing to This Repository

To maintain the quality and integrity of the repository, please adhere to the following guidelines:

- Make sure all commits have a clear and concise message.
- Document any major changes or decisions in the meeting notes.
- Review and merge changes through pull requests to ensure oversight.

## Getting Help

If you encounter any issues or have questions about how to contribute, please refer to the [ESIIL Support Page](https://esiil.org/support) or contact the repository maintainers directly.

## Customize Your Repository

As a new working group, you'll want to make this repository your own. Here's how to get started:

1. ~~**Edit This Readme**: Replace the placeholder content with information about your specific project. Ensure that the introduction, project overview, and objectives clearly reflect your group's research focus.~~

2. ~~**Update Bio**: Add details about your expertise, role in the project, and professional background. Include links to personal or professional web pages to foster community engagement and collaboration.~~

3. ~~**Organize Your Code**: Structure your codebase in a way that is logical and accessible. Use directories and clear naming conventions to make it easy for all members to find and contribute to different parts of the project.~~

4. **Document Your Data**: Include a data directory with README files explaining the datasets, sources, and any preprocessing steps. This will help new members understand and work with the project's data effectively.

5. **Outline Your Methods**: Create a detailed METHODS.md file where you describe the methodologies, software, and tools you will be using in your research. This transparency will support reproducibility and collaborative development.

6. **Set Up Project Management**: Utilize the 'Issues' and 'Projects' features on GitHub to track tasks, discuss ideas, and manage your workflow. This can help in maintaining a clear view of progress and priorities.

7. **Add a License**: Choose and include an appropriate open-source license for your project, ensuring that the broader community understands how they can use and contribute to your work.

8. **Create Contribution Guidelines**: Establish a CONTRIBUTING.md file with instructions for members on how to propose changes, submit issues, and contribute code.

9. **Review and Merge Workflow**: Decide on a workflow for reviewing and merging changes. Will you use branch protection? Who will have merge privileges? Document this process to avoid confusion.

10. **Establish Communication Channels**: Beyond GitHub, set up additional communication channels like Slack, Discord, or email lists for quick and informal discussions.

Remember, the goal is to make your repository clear, accessible, and useful for all current and future members of your working group. Happy researching!
