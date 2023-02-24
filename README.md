#### Project Status - Complete
# Client-or-Company-Dataset
## Creating a Clients/Comapnies Dataset using Python
### Introduction
A client requested for the creation of a dataset of their potential customers. These customers are institutions that requires their services. Prior to this request, the client rely on dataof potential clients who have made contact enquiries about the services provided by the client including those made via emails, phone calls, the business website, social media and other marketing channels. 

Although specific clients of the company can be identified through other channels like looking into the correlation between their clients, sector, location, to mention a few, datasets acquired by the clients business itself, if successful, could have some advantage over the other channels because it can be applied to target customers/business' who could be missed by the other marketing channels. 

Creating this kind of dataset for the client's business was quiet challenging. I demonstrate here how I carried out the task using Python. For this demo, I used the UK Governments Companies House database at [data.gov.uk](https://data.gov.uk/dataset/4462e41a-7413-4359-97f5-420b6ca5f9c0/basic-company-data). I selected this database for this project because it contains data of the parent companies and/or branches of every business in the UK hence it was deemed perfect for demonstrating of how the task could be carried out to create the clients database.

To successfully execute the task, I use the following approach:

- download the companies data from UK Government's Companies House database as zip files into the working directory using a list of their URLs and a conditional **for loop statement**,

- unzip and extract all the data from the files using a conditional **for loop** statement,

- merge the files, and 

- write the files into a CSV file for easy assessibility by the client.

### Technologies and modules Use

- `Jupyter notebook` 

- `Pandas`

- `Os.path` for retrieving data using path names, merging, normalizing

- `Urllib.request`to fetch web data

- `Zipfile` to read, write, append and create ZIP files

- `Glob` to retrieve files from directory or pathnames matching a specified pattern.

### Contribution
Thanks for considering making a contribution to this project.

### Contact
All feedback would be warmly recieved.
