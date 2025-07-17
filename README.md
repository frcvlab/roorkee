# roorkee
Data files and scripts for the Roorkee Surname study

[Extract from research paper: An Irish Overseer in colonial India: a case study, Lyons&Lyons 2025 in review]

To identify the Irish contingent at Roorkee the original data pertaining to students was extracted from the Thomason College of Civil Engineering (now the India Institute of Engineering Roorkee) Calendar for 1871-72, pages 119 through 135 which list the names, graduation years and present appointments of students in the Upper Subordinate class in alphabetical order of surname for the years 1848 through 1871. The pages were scanned using OCR (Optical Character recognition) to generate a spreadsheet with the tabular data. Each page was checked manually against the Calendar for accuracy. The data was also checked against the listing of graduates by year on pages 61 through 111 of the Calendar. Six additional names were found for the year 1871 that were not in the alphabetical listing, and they were added manually to the data. The spreadsheet data was filtered to yield a list of surnames. Surname ethnicity was established using the Geneanet surname database. This online resource lists the source texts used to classify the surname ethnicity and was chosen for this reason. However, the texts used by this database are all modern texts, and to determine how much error was introduced by using modern sources, a uniform sample of 10% of the names was made and ethnicities identified using MacLysaght  and compared to the Geneanet results. MacLysaght differed from Geneanet on only 5% of the sample (3 of 59 surnames), lending confidence to the use of Genenanet.  

uppersubordinate_wsurname.csv -- spreadsheet with names and ethnicities extracted as above for the upper subordinate class
engineer_class_wsurname.csv -- spreadsheet with names and ethnicities extracted as above for the engineer class
engineer surnames_wethnicity.json -- JSON format file with a list of names and ethnicites for those names  from Geanet for the engineer class
surnames_wethnicity.json -- JSON format file with a list of names and ethnicites for those names  from Geanet for the uppersubordinate class
RoorkeeNames.txt -- text file with an alphabetical list of names and ethnicities from the Upper Subordinate class
Sample_of_RoorkeeNames.txt -- text file with an alphabetical list of names comoprising a random sample of 10% of RoorkeeNames.txt for testing against MacLysaght
