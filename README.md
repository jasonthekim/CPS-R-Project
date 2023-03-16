## Introduction
This project was done through R programming. The main goal was to investigate child removals within the context of CPS (Child Protective Services) in the context
of other public services, specifically families with kinship assistance and information about calls per hotlines within a region.

## Information on Datasets
For the Texas Removal’s dataset (from Texas.gov), this dataset provides information on child removals by region in Texas along with demographic information such as gender,
race/ethnicity, and age. The data is provided by the Texas Department of Family and Protective Services (DFPS) and covers the period from 2013 to 2022. Each row in the dataset
represents one removal event and includes information on the fiscal year, region, removal stage, gender, race/ethnicity, age, and number of removals. The removal stage is categorized
as either during family protection or the investigative stage. The regions are defined by the DFPS and are based on the state’s 12 Health and Human Services Commission (HHSC)
regions.

This dataset can be useful for researchers, policymakers, and others interested in understanding the characteristics of child removals in Texas over time and by region. It could also be
used to identify trends or disparities in child removal rates across demographic groups. 

The Families Receiving Kinship Monetary Assistance dataset (Texas.gov) is another dataset
that provides information on families receiving monetary assistance through the Texas Kinship Caregiver Program, which is a program that provides financial assistance to eligible relatives
who care for children in their homes due to a child’s removal from their biological parents. The dataset covers the period from 20103to 2022 and is also provided by the Texas Department of
Family and Protective Services (DFPS). Each row in the dataset represents one county and includes information on the fiscal year, county, region, and the number of families receiving
monetary assistance through the program. The regions are based on the state’s 12 Health and Human Services Commission (HHSC) regions. The program provides eligible families
with monthly financial assistance to cover the basic needs of the children in their care, such as food, clothing, and shelter. This dataset can be useful for researchers, policymakers, and
others interested in understanding the characteristics of families receiving monetary assistance
through the Texas Kinship Caregiver Program over time and by county. It could also be used
to identify trends or disparities in program utilization across different regions of the state.
While these datasets contain different information on child welfare services in Texas, it is
possible that they could be joined using common variables such as county/region or year,
if present in both datasets. For example, if both datasets include the region variable, they
could be joined using that variable to compare the number of families receiving monetary
assistance through the Texas Kinship Caregiver Program to the number of removals in each
region. This could provide insights into how well the program is meeting the needs of families
who have had children removed from their homes. In terms of variable types, the first dataset
contains a mix of categorical and numeric variables. Categorical variables include gender,
race/ethnicity, and removal stage, while numeric variables include age and number of removals.
The second dataset contains mostly categorical variables, with the exception of the number
of families receiving monetary assistance which is a numeric variable. Potential relationships
