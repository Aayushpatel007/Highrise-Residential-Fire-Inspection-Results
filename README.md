# Highrise-Residential-Fire-Inspection-Results



This project will analyze all indicated properties where violations have been found by an Inspector which are required to be fixed for compliance at the time with the Ontario Fire Code as well as properties with no observable violations. This dataset only includes 'Closed' Cases indicating that the inspection process has ended.

We can find out what are the common areas where violations with help of its Violation.code/ Fire code and Violation.description have been found. Additionally, what kind of violations have been found by an inspector most of the time and least common violations.
Inspections that have commenced and are ongoing will not be available in the dataset until all related processes have ended. Any buildings that have an immediate threat to occupant or firefighter safety are required to implement temporary measures until Fire Code violations are corrected.

## Column	Description: 

      _id	: Unique row identifier for Open Data database
      Inspections.ClosedDate:	Date TFS closed inspection file
      inspections.OpenedDate:	Date TFS opened inspection file
      latitude:	Latitude
      longitude:	Longitude
      propertyAddress:	Address of inspected property
      propertyWard:	Ward of inspected property based on 2019 boundaries
      violations.violationDescription:	Description of fire code under which violation was noted
      violations.violationFireCode:	Fire code under which violation was noted


Total categories for Violation/fire code using its description : 373
No of missing values in dataset: 6114
Total rows: 23914

<img src="https://github.com/Aayushpatel007/Highrise-Residential-Fire-Inspection-Results/blob/master/map2.png" width="950" height="650" style="vertical-align:center;">


### Top 10 violations code and description found by instructor: 

('2.2.3.2 Maintenance of closures', 2208), 
('2.4.1.1 Accumulation of combustible materials', 1112), 
('2.2.2.1 Damaged fire separations', 978), 
('6.3.1.4 Fire Alarm Maintenance', 728),
('2.8.2.1 Measures in a fire safety plan', 590),
('2.2.3.1 Damaged closures', 477),
('6.5.1.5 Obstructions', 458),
('2.16.2.1 Installation requirements', 442),
('1.1.2.3./6.3.2.2. Records of Test (Fire Alarm)',441

