This website contains data, statistics and visualizations used in the publication "Was wird denn hier gespielt? Genrebezogene Unterschiede der digitalen Spielelandschaft in Deutschland und Japan", published in Spielzeichen IV (2023).

The data and visualizations can be found in the related [github repository](https://github.com/m4chi/diggrdata_GenreGerJap).

The data is used in my ongoing research project on videogame spatialization, and may be updated and extended over time. For stable versions, please refer to the Zenodo upload specified in the respective research output.

Large portions of the data have been aggregated with the [diggr tools](https://github.com/diggr/) and edited manually thereafter. For the purpose of this research, I rely on a dataset retrieved from Mobygames.com on April 26, 2019, with their kind support. This research has received support from the DFG.

## 1. Overlap of titles per platform for Germany and Japan

The following table contains the raw data for the overlap between game titles on all relevant platforms between Japan and Germany, which was included in the article in an abbreviated form (Table 1). Note that the original data could not be checked for quality and completeness across all platforms - as such, the data is a rough approximation of the empirical reality.

[Cross-country overlap of videogame titles per platform](data/JP_GER_quantitycomparison_finApril2022.csv)

## 2. Regional Genre Cultures

In order to facilitate the research, I have created a table containing teh quantitative distribution of genre labels for each platform for the releases in Germany and Japan, using the 15 genre categories provided by Mobygames as basis.

[Basic Genres](data/Genre_quantitylist_GERJP_catBasicGenres.csv)
[Gameplay](data/Genre_quantitylist_GERJP_catGameplay.csv)
[narrative Theme / Topics](data/Genre_quantitylist_GERJP_catNarrativeThemeTopic.csv)
[Setting](data/Genre_quantitylist_GERJP_catSetting.csv)
[Sports Themes](data/Genre_quantitylist_GERJP_catSportsThemes.csv)
[Vehicular Themes](data/Genre_quantitylist_GERJP_catVehicularThemes.csv)

For the other genre categories, please see the [repository's data folder](data/).

The data was visualized in a series of bar plots:

[![Basic Genres Comparison plot](visualizations/genre_comp_JPGER__c_BasicGenres__p_all_percent_barh.png)](visualizations/genre_comp_JPGER__c_BasicGenres__p_all_percent_barh.png)

[![Gameplay Genres Comparison plot](visualizations/genre_comp_JPGER__c_Gameplay__p_all_percent_barh.png)](visualizations/genre_comp_JPGER__c_Gameplay__p_all_percent_barh.png)

[![Narrative Theme / Topic Comparison plot](visualizations/genre_comp_JPGER__c_NarrativeThemeTopic__p_all_percent_barh.png)](visualizations/genre_comp_JPGER__c_NarrativeThemeTopic__p_all_percent_barh.png)

[![Setting Comparison plot](visualizations/genre_comp_JPGER__c_Setting__p_all_percent_barh.png)](visualizations/genre_comp_JPGER__c_Setting__p_all_percent_barh.png)

[![Sports Themes Comparison plot](visualizations/genre_comp_JPGER__c_SportsThemes__p_all_percent_barh.png)](visualizations/genre_comp_JPGER__c_SportsThemes__p_all_percent_barh.png)

[![Vehicular Themes Comparison plot](visualizations/genre_comp_JPGER__c_VehicularThemes__p_all_percent_barh.png)](visualizations/genre_comp_JPGER__c_VehicularThemes__p_all_percent_barh.png)


## 3. Historical development

In addition to aggregating the data across different platforms, I have also created a historical timeline of the shares particular genre have assumed in each country:

[![Historical development of Basic Genres in Japan for PC](visualizations/genredist_timeline_JPGER__cat1_pc_Japan.svg)](visualizations/genredist_timeline_JPGER__cat1_pc_Japan.svg)

[![Historical development of Basic Genres in Germany for PC](visualizations/genredist_timeline_JPGER__cat1_pc_Germany.svg)](visualizations/genredist_timeline_JPGER__cat1_pc_Germany.svg)


[![Historical development of Sports Themes in Japan for all platforms](visualizations/genredist_timeline_JPGER__cat3_all_Japan.svg)](visualizations/genredist_timeline_JPGER__cat3_all_Japan.svg)

[![Historical development of Sports Themes in Germany for all platforms](visualizations/genredist_timeline_JPGER__cat3_all_Germany.svg)](visualizations/genredist_timeline_JPGER__cat3_all_Germany.svg)

For a more comprehensive set of visualizations, please consult the [repository's visualization folder](visualizations/).

# Meta

<!--- **Zenodo Repository Snapshots
[![DOI](https://zenodo.org/badge/326400336.svg)](https://zenodo.org/badge/latestdoi/326400336) --->

**License**
[CC-BY 4.0](http://creativecommons.org/licenses/by/4.0)
![license](https://i.creativecommons.org/l/by/4.0/80x15.png)

**Copyright**
2023 Martin Roth [research@asobiba.de](research@asobiba.de)

<!--
# diggrdata_FromSoftware

This site augments my publications on the spatialization of videogame production, distribution and reception in the case of the Japanese company FromSoftware.
This research is currently published or accepted for publication as follows:

- Roth, Martin (ロート　マーティン). Accepted, 2021. テレビゲーム文化の空間的展開：FromSoftwareゲームの生産的・流通的展開とそれにおけるソフトな文化的境界線. [Replaying Japan](https://www.rcgs.jp/?page_id=200), Vol. 3.

The site features interactive and non-interactive visualizations used for or resulting from my analysis of the data stored in the [diggrdata_FromSoftware repository](https://github.com/m4chi/diggrdata_FromSoftware). For more information, see the [README](README.md).
The data is used in my ongoing research project on videogame spatialization, and will be updated and extended over time. For stable versions used in my research, please refer to the Zenodo snapshot specified in the respective research output.


## 1. FromSoftware Production

### 1.1. FromSoftware Collaborators per game per country

The following figures provide an overview of the companies involved in the production of FromSoftware games, based on datasets [1. FromSoftware DataTable](/data/FromSoftware_Tulpa_DataTable_edited20210105.csv) and [2. FromSoftware Production Network based on Mobygames Release Data](/data/). Click on the image for a higher resolution version.

[![Headquarter Locations of Companies involved in FromSoftware games](visualizations/FromSoftware_ReleaseAnalysis_CompanyLocations.svg)](visualizations/FromSoftware_ReleaseAnalysis_CompanyLocations.svg)

[![Role-based chart of company locations, divided into two groups, a.) Japan, b.) other countries](visualizations/FromSoftware_Rolebased_companyCountries.svg)](visualizations/FromSoftware_Rolebased_companyCountries.svg)

### 1.2. FromSoftware Production Network based on Mobygames Release Data

The following figures depict the production networks of companies involved in FromSoftware games according to the release data on Mobygames.com, based on the dataset 2. FromSoftware Production Network [nodelist](/data/FromSoftware_ProductionNetwork_MobygamesReleaseBased20201005_nodes.csv) and [edgelist](/data/FromSoftware_ProductionNetwork_MobygamesReleaseBased20201005_edges.csv). Edges are based on contribution to the same game (collaboration network). Nodes are defined for each company in each distinct role it takes on. Company location was added where available via Wikidata. The data was created with [diggr lemongrab](https://github.com/diggr/lemongrab) and edited manually in Gephi 0.9.2 to add statistical data, as well as to include several country data missing on Wikidata and a country based color hex code, following this color schema:

![this hex color schema](visualizations/FromSoftCountryColorCodesTable.png)

The following network visualization shows all actors, meaning any companies in any role involved in producing a FromSoftware game.

[![FromSoftware Production Network, all collaborators](visualizations/FromSoftware_ProductionNetwork_withroles_all.svg)](visualizations/FromSoftware_ProductionNetwork_withroles_all.svg)

The following network visualization excludes the actors who take on functions needed when publishing a game outside of Japan, such as "localization."

[![FromSoftware Production Network, limited collaborators](visualizations/FromSoftware_ProductionNetwork_withroles_nopubldistrloc.svg)](visualizations/FromSoftware_ProductionNetwork_withroles_nopubldistrloc.svg)


## 2. FromSoftware Distribution

### 2.1. Distribution Overview

The following visualizations show the historical change in the regional distribution of FromSoftware games. They are based on the dataset [1. FromSoftware DataTable](/data/FromSoftware_Tulpa_DataTable_edited20210105.csv) and [3. FromSoftware Release Data](/data/FromSoftware_releases.json).

Number of releases per region per game
[![Per-game releases per region, stacked](visualizations/FromSoftware_ReleaseAnalysis_ReleaseRegion.svg)](visualizations/FromSoftware_ReleaseAnalysis_ReleaseRegion.svg)

First release region distribution
[![Distribution of first releases by region](visualizations/FromSoftware_ReleaseAnalysis_FirstReleaseCountryDistribution.svg)](visualizations/FromSoftware_ReleaseAnalysis_FirstReleaseCountryDistribution.svg)

Temporal distance between first release in Japan and first release in US and EU
[![Temporal Distance between first release in Japan and first release in the US and EU region](visualizations/FromSoftware_ReleaseAnalysis_ReleaseDistanceJPEUUS.svg)](visualizations/FromSoftware_ReleaseAnalysis_ReleaseDistanceJPEUUS.svg)

### 2.2. Release Timeline

The following link takes you to an interactive visualization of all available FromSoftware game releases in Japan (JP), Europe (EU) and North America (US) mapped on a timeline with various additional information about each game. The visualization was created with [diggr tulpa](https://github.com/diggr/tulpa). Provenance information is available, added with [diggr provit](https://github.com/diggr/provit).

[Interactive Release Timeline](visualizations/fromsoft_release_release_timeline.html)

# Meta

**License**
[CC-BY 4.0](http://creativecommons.org/licenses/by/4.0)
![license](https://i.creativecommons.org/l/by/4.0/80x15.png)

**Copyright**
2021 Martin Roth [research@asobiba.de](mailto: research@asobiba.de)
-->
