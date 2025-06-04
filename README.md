# Impact of midwife continuity of carer on stillbirth rate and first feed in England 
## Analysis produced as part of an MRES at the University of Leeds in affiliation with NHS England Data & Analytics

### About the Project

[![status: archive](https://github.com/GIScience/badges/raw/master/status/archive.svg)](https://github.com/GIScience/badges#archive)

**Note:** No data is shared in this repository 

### Project Stucture TBD

- The main pipeline code is split into 3  and is found in the root of the repository. `Please see Usage below for more information`
- The accompanying [report](./reports/report.pdf) is also available in the `reports` folder
- More information about the code usage can be found in the [model card](./model_card.md)
- {OTHER REPO STRUCTURE}

### Built With

[![R version 4.2.1 ](https://img.shields.io/badge/R-v4.2.1-blue.svg)]([https://www.r-project.org/])
[![pandas version 1.2.1.2 ](https://img.shields.io/badge/pandas-v1.21.2-blue.svg)]([https://pandas.pydata.org/pandas-docs/stable/whatsnew/v1.2.1.html#])

### Getting Started
This code uses standard data processing techniques and statistical tests applied to a specific dataset. 
As such, it is not viewed as "a custom algorithm or software central to the paper and has not been reported previously in a published research paper", so is not at production standard for those without access to NHS England's secure Data Access Environment, 
which is strictly controlled given the need to ensure patient confidentiality, but is being made available to maximise transparency.

#### Installation

To clone the repo:

`git clone https://github.com/C-HALL/MCoC`

To use the code 'as-is' you will need:
 `Access to NHS England's internal secure data environment`
 `Access to the Maternity Services Dataset`

Alternatively, to replicate thie piece of work outside of NHS England, you will need to apply for access to Maternity Services Dataset through the [Dataset Access Request Service (DARS)](https://digital.nhs.uk/services/data-access-request-service-dars#apply-through-dars-online). Then edit the queries to use the Maternity Services Dataset DARS data structure.


Please contact [chris.roebuck@nhs.net](mailto:chris.roebuck@nhs.net), [charlotte.atherden@nhs.net](mailto:charlotte.atherden@nhs.net) or [k.parkyn@nhs.net](mailto:k.parkyn@nhs.net) with any questions about using or adapting the code. 

### Usage
The main pipeline is run first. The main pipline is split into three. Part 1 contains SQL code. Part 2 the Pandas code. Part 3 contains R code. The output of Part 1 feeds into the start of Part 2. The output of Part 2 feeds into the start of Part 3. 

The final stage of the pipeline in R Studio involves reformatting and creating additional derivations to underpin the statistical analysis, followed by running the statistical analysis. A minimum set of core fields were exported from the Pandas section of the pipeline.


#### Outputs
{LIST AND DESCRIPTION OF OUTPUTS TBD}

{NOTES ON REPRODUCIBILITY OF RESULTS TBD}

#### Datasets
This data uses the Maternity Services Dataset (MSDS).
[Information on the dataset.](https://digital.nhs.uk/data-and-information/data-collections-and-data-sets/data-sets/maternity-services-data-set/)
[Metadata.](https://digital.nhs.uk/data-and-information/data-collections-and-data-sets/data-sets/maternity-services-data-set/guidance?area=metadata)
[Technical Output Specification (TOS) and Data Model.](https://digital.nhs.uk/data-and-information/data-collections-and-data-sets/data-sets/maternity-services-data-set/tools-and-guidance)

### Contributing

This project is in archive and is not currently being worked on, therefore we are not requesting any contributions to this project.  

### License

The documentation is [© Crown copyright][copyright] and available under the terms
of the [Open Government 3.0][ogl] licence.

[copyright]: http://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/crown-copyright/
[ogl]: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

### Contact

Please feel free to contact the authors of the paper at [chris.roebuck@nhs.net](mailto:chris.roebuck@nhs.net), [jane.sandall@kcl.ac.uk](mailto:jane.sandall@kcl.ac.uk), [R.M.West@leeds.ac.uk](mailto:R.M.West@leeds.ac.uk), [k.parkyn@nhs.net](mailto:k.parkyn@nhs.net), [charlotte.atherden@nhs.net](mailto:charlotte.atherden@nhs.net) and [O.A.Johnson@leeds.ac.uk](mailto:O.A.Johnson@leeds.ac.uk). 

<!-- ### Acknowledgements -->

