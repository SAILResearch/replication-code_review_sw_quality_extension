# Replication Package for "An Empirical Study of the Impact of Modern Code Review Practices on Software Quality"

Shane McIntosh, Yasutaka Kamei, Bram Adams, and Ahmed E. Hassan  
[Empirical Software Engineering Journal, vol. 21, issue 5, 2015](https://doi.org/10.1007/s10664-015-9381-9)

Abstract: Software code review, i.e., the practice of having other team members critique changes to a software system, is a well-established best practice in both open source and proprietary software domains. Prior work has shown that formal code inspections tend to improve the quality of delivered software. However, the formal code inspection process mandates strict review criteria (e.g., in-person meetings and reviewer checklists) to ensure a base level of review quality, while the modern, lightweight code reviewing process does not. Although recent work explores the modern code review process, little is known about the relationship between modern code review practices and long-term software quality. Hence, in this paper, we study the relationship between post-release defects (a popular proxy for long-term software quality) and: (1) code review coverage, i.e., the proportion of changes that have been code reviewed, (2) code review participation, i.e., the degree of reviewer involvement in the code review process, and (3) code reviewer expertise, i.e., the level of domain-specific expertise of the code reviewers. Through a case study of the Qt, VTK, and ITK projects, we find that code review coverage, participation, and expertise share a significant link with software quality. Hence, our results empirically confirm the intuition that poorly-reviewed code has a negative impact on software quality in large systems using modern reviewing tools.

## Bibtex

```bibtex
@Article{McIntosh2016,
author="McIntosh, Shane
and Kamei, Yasutaka
and Adams, Bram
and Hassan, Ahmed E.",
title="An empirical study of the impact of modern code review practices on software quality",
journal="Empirical Software Engineering",
year="2016",
month="Oct",
day="01",
volume="21",
number="5",
pages="2146--2189",
issn="1573-7616",
doi="10.1007/s10664-015-9381-9",
url="https://doi.org/10.1007/s10664-015-9381-9"
}
```

## Data
    
- VCS commit and gerrit code review data (MySQL dump, 45 MB)
- Component-level data (CSV, 176 KB) 

These files can be downloaded [here](https://github.com/SAILResearch/replication-code_review_sw_quality/releases/latest)

## Additional Figures

(RQ1) Coverage - Variable Clustering

- [Qt 5.0](figures/revrate/qt50_varclus.pdf)
- [Qt 5.1](figures/revrate/qt51_varclus.pdf)
- [VTK](figures/revrate/vtk_varclus.pdf)
- [ITK](figures/revrate/itk_varclus.pdf)

(RQ1) Coverage - Spearman multiple ρ2

- [Qt 5.0](figures/revrate/qt50_spearman2.pdf)
- [Qt 5.1](figures/revrate/qt51_spearman2.pdf)
- [VTK](figures/revrate/vtk_spearman2.pdf)
- [ITK](figures/revrate/itk_spearman2.pdf)

(RQ1) Coverage - Additional tables

- [Alternative variables](figures/extra_tables/revrate_extra.pdf)

(RQ2) Participation - Variable Clustering

 - [Qt 5.0](figures/participation/qt50_varclus.pdf)
 - [Qt 5.1](figures/participation/qt51_varclus.pdf)
 - [ITK](figures/participation/itk_varclus.pdf)

(RQ2) Participation - Spearman multiple ρ2
 
- [Qt 5.0](figures/participation/qt50_spearman2.pdf)
- [Qt 5.1](figures/participation/qt51_spearman2.pdf)
- [ITK](figures/participation/itk_spearman2.pdf)

(RQ3) Expertise - Variable Clustering

 - [Qt 5.0](figures/expertise/qt50_varclus.pdf)
 - [Qt 5.1](figures/expertise/qt51_varclus.pdf)
 - [ITK](figures/expertise/itk_varclus.pdf)

(RQ3) Expertise - Spearman multiple ρ2

- [Qt 5.0](figures/expertise/qt50_spearman2.pdf)
- [Qt 5.1](figures/expertise/qt51_spearman2.pdf)
- [ITK](figures/expertise/itk_spearman2.pdf)
