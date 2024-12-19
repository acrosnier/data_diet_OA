
Data collection: environmental impacts from Agribalyse and Ecoinvent using OpenLCA en Simapro (more details in the section “Methods” of the article) (results in Modelling_data/LCA impacts/OpenLCA.xlsx and Modelling_data/LCA impacts/SIMAPRO.xlsx)
Data processing for all scenarios and impacts computations for the reference scenario 2018 with data_processing.ipynb
Excel models : for each 2050 scenario, a fork to farm approach is implemented to compute the crop mass, livestock and land use necessary given a diet.
The results (crop mass, livestock and land use for 2050 scenarios) are summarized in Modelling_data/Environmental impacts/calculs_impacts_scenarios.xlsx

Environmental impact computations and graphs with impact_assessment.ipynb

Scenario equivalence

BAUlancet ⇒ ConvEAT in paper
OAlancet ⇒ OrgEAT in paper
BAUswiss ⇒ ConvSFP in paper
OAswiss ⇒ OrgSFP in paper

data_processing.ipynb
contains the data processing part done using Python and impact computations of the reference scenario 2018

impact_assessment_12-06-24.ipynb

Folder “Excel models”
contains the Excel model for the scenarios, mainly a fork to farm approach to compute the crop mass, livestock and land use necessary given a diet, considering food waste, losses, feed, self-sufficiency ratio, yields …
About
This repository contains the complete data code of the paper 'Analyzing organic agriculture’s potential to nourish, preserve, and outperform conventional farming in Switzerland', by Agathe Crosnier, Gino Baudry, Laurence Jeangros and Philippe Thalmann


