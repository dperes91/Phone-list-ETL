# Project Description
For this project, the client had databases in .vcf format from various cell phones of each of their branches, as well as data stored in .csv files from the personnel management system.

The goal was to create a valid contact list for each store to use in promotional actions aimed at attracting new customers.

In the end, a file containing only valid contacts per store was generated, and these contacts were later imported via Google Contacts, synchronizing with each store's cell phones.

## Steps to Achieve the Objective

#### 1. Data Collection:

Gather all .vcf files from the cell phones of each branch.
Collect the .csv files from the personnel management system.

#### 2. Data Conversion and Normalization:

Convert the .vcf files to a more manageable format like .csv using an appropriate library or tool (e.g., vcf2csv).
Ensure that contact data, such as names, phone numbers, emails, etc., are in standardized formats.

#### 3. Data Consolidation:

Combine the converted .vcf data and the .csv data into a single database.
Remove duplicates to ensure each contact appears only once in the final list.

#### 4. Contact Validation:

Verify the validity of phone numbers and emails using format validation tools and, if possible, real-time validation services.
Exclude invalid or outdated contacts.

#### 5.Store Segmentation:

Classify contacts by store/branch using available information (e.g., location, store code, etc.).
Create separate lists for each store based on this classification.

#### 6.Generating Contact Lists:

Export the segmented lists to an appropriate format (e.g., .csv or .xlsx) to facilitate their use in promotional actions.


#### 7. Importing Contacts:

Import the validated contact lists into Google Contacts, synchronizing them with each store's cell phones.
