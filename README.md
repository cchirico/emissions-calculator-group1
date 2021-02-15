# Emissions Calculator Group 1
## Hello and welcome!
#### This is group 1's project diary. As part of ENE425 Sustainable Energy's assessment, students are tasked with developing a *software application* to work out the transport carbon emissions of each group. The objective of the app is to explore how technology, public policy and our own personal decisions could contribute towards mitigating carbon emissions. This section is meant to be kept up to date so that everyone is able to follow the project as it progresses.

Directory Tree:

    +---Emissions_App
    |   app.py
    |   LICENSE
    |   Output_tree.doc
    |   Procfile
    |   python-app.yml
    |   requirements.txt
    |   
    +---notes
    |       .gitkeep
    |       module_design_v2.png
    |       
    +---static
    |       favicon.png
    |       
    \---templates
            add_record.html
            edit_or_delete.html
            error.html
            index.html
            list.html
            login.html
            result.html
            select_record.html

## Emissions Methodology
### This section will contain information on emissions calculation method for transport sources:
#### Defining the term "Vehicle"
To have a basic understanding it is important to have a classification of transport as urban transport or industrial transport (e.g. maritime, air). For a more segregated classification of the term "vehicle" under EC standards, this [link](https://www.eafo.eu/knowledge-center/european-vehicle-categories), connected to the last study of ["Determining the Environmental Impacts of Conventional and Alternatively Fuelled Vehicles Through LCA"](https://ec.europa.eu/clima/sites/clima/files/transport/vehicles/docs/2020_study_main_report_en.pdf) by Ricardo Energy and Environment for the European Comission. The segregation used in this study is practical for our purposes. However, a more advanced methodology is used than what is our intention with this app. 

#### Conversion Factors for Greenhouse Gas Reporting
[Here](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/891105/Conversion_Factors_2020_-_Condensed_set__for_most_users_.xlsx) are the conversion factors used by UK and international organisations to report on 2020 greenhouse gas emissions. For instance, one can find how many kilograms of CO2 emissions the different car types 

