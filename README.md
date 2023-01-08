# CovFSA
This is the repository for agent-based simulation, extension algorithms and datasets with results.  
* Simulation-Long Covid & reinfection.ipynb -- The main file to run the simulation with pre-assumed hyper-parameters about the case study in Shenzhne, such as the population information, the contact rates and the transmission rates related to the Omicron virus.  
* Extension algorithm.ipynb -- The extension algorithm script that could resacle the simulation results into different levels, such as from District to City.  
* synthetic population.csv & workplace information -- The data sets required for simulation in Shenzhen's case study.


##　How to use the CovFSA  
1. Download the two jupyter notebooks and datasets requried found into the local PC.    
2. Run the Simulation-Long Covid & reinfection.ipynb step by step following the commented codes, which guide users to replace some hyper-parameters to suite various case studies.  
** note: a. Some third-party packages might be installed by pip install-- or conda way.  
         b. The file path to save the simulation results could be changed due to users' own path names.  
3. Run the Extension algorithm.ipynb to rescale the simulation results accordting to flexible requirements and plot the results.  
## Open data sources
There are references for the open datasets that authors used to generate and colllect for agents' heterogenious attributes.
1. Bulletin of the seventh National Census of Futian District, Shenzhen City, http://tjj.sz.gov.cn/ztzl/zt/szsdqcqgrkpc/, 2021  
2. Main data Bulletin of the fourth National Economic Census of Futian District, Shenzhen City, http://tjj.sz.gov.cn/zwgk/zfxxgkml/tjsj/tjgb/content/post_7294578.html, 2020
3. Quarterly Report on Economic and Social Development Data of Futian District of Shenzhen in the fourth quarter of 2021, http://www.szft.gov.cn/bmxx/qtjj/sjfb/, 2022  
4. Shenzhen Statistical Yearbook 2021, http://tjj.sz.gov.cn/zwgk/zfxxgkml/tjsj/tjnj/, 2022
5. Shenzhen Housing Development 2020 annual implementation plan, http://zjj.sz.gov.cn/attachment/0/683/683940/9597084.pdf, 2020
