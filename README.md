# otaku
Statistical analysis of and modeling of US infrastructure vulnerabilities to COVID-19

## Background
This study utilizes public data about US critical infrastructure sectors in order to attempt to highlight potential challenges which may be faced in keeping the lights on and the water running during the COVID-19 pandemic.  The study is currently being completed as a course project for the Sustainable and Resilient Infrastructure Systems program at the University of Illinois at Urbana-Champaign, and in no way reflects official work or policy of the United States Federal Government or the United States Department of the Army.  This unofficial nature is reflected in the name of the study, Otaku, borrowed from Max Brooks' book World War Z's discussion of computer modeling using public data.

## Instructions
Make sure to update the data daily.  All of the code is designed to work with the folder, so nothing else should require changes unless data structure changes.  Note however this is not the most efficient way because all data must be reloaded, eventually I may implement a database and data pipeline.

### JHU Data
cd C:\users\garfink2\documents\data\covid\covid-19
git pull

### NYT Data
cd C:\users\garfink2\documents\data\covid\covid-19-data
git pull

## Tasks for public version of analysis
- [x] Make map of USA water supplies by size
- [x] Estimate water treatment plant staffing
- [x] Fix leading zero bug for GEOID
- [ ] Calculate cumulative cases and deaths
- [ ] Estimate how much staff is necessary for operations, even if very coarse
- [ ] Standardize water treatment staffing per area
- [x] Have duplicated columns in gdf counties water, fix this!!!
- [x] Standardize water treatment staffing per population served
- [ ] Set up simple models for likelihood of outcome based on age and pre-existing condition
- [ ] Set up a slider for staffing requirements and disease parameters and link to change colors if exceeded
- [ ] Clean up code and add text to make a clear report
- [x] Figure out what is wrong with Florida wastewater
- [x] Add pretty print names to make the graphics look nicer
- [x] Outline around counties which contain Army installations

## Tasks for non-public analysis
- [ ] Make map of every water treatment plant (civilian and Army)
- [ ] Make map of every power plant (civilian and Army)
