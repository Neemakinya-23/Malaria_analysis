# Malaria_analysis
**Data Source**
The dataset was obtained from the Kenya Data Portal in DTA (Stata) format. Initially, I faced challenges reading this format in R, but learned to use the haven package to properly import and work with the data.

```
# Install required package if needed
install.packages("haven")

# Load the package
library(haven)

# Read the Stata (.dta) file
children_record <- read_dta("path/to/your/file/KEKR81FL.DTA")

# View the first few rows
head(children_record)
```
# During this analysis
I familiarized myself with standard malaria indicators and coding conventions used in global health datasets. 
Below are some key terms and their representations in the data: 
ml13e: Binary indicator for whether a child was tested for malaria
0 = No
1 = Yes

s406: "Told child had malaria" (diagnosis result)
0 = No
1 = Yes
2 = Don’t know

# Simplified Data Workflow
Imported data using haven::read_dta()
Reduced columns to only malaria-relevant variables
Converted coded values to readable factors
Performed analysis on this simplified dataset

# visualizations







