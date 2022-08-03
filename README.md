# sigSPLICE
Single cell splicing analysis of Pancreatic Neuroendocrine Cancer

## Table of Contents

- [Template](#team-repo-template)
    - [Background](#Background)
    - [Data](#data)
    - [Usage](#usage)
        - [Installation](#installation)
        - [Requirements](#requirements) _Can be named Dependencies as well_
        - [Activate conda environment](#activate-conda-environment) _Optional_
 
    - [Results](#results) _Optional depending on project_
    - [Team Members](#team-members)

## Background
Alternative splicing causes generation of distinct mRNA from the single gene resulting in structural or functional protein isoforms. Splicing is conducted by splicesome comprised of a complex molecular machinery in the eukaryotic cells. Cancer cells exhibits cell type specific alterations in the splicing process that invokes a prognostic/therapeutic value and can also serve as biomarkers for cancer diagnosis. The transcriptomic landscape of the cancer cells engender vulnerability to inhibition of splicing, thus can be targeted therapeutically. sigSPLICE will delineate unique splicing signatures in Pancreatic Neuroendocrine Cancer that will unravel novel biomarkers for cancer detection and targets for pharmacological intervention. 

## Data

:exclamation: _Discuss the data you used and how it can be accessed._ :exclamation:

## Usage

### Installation

git clone -b main \
    git@github.com:u-brite/team-repo-template.git
```

### Requirements
:exclamation: _Note any software used (including Python or R packages), operating system requirements, etc. and its version so that your project is reproducible. It does not have to be in the below format_ :exclamation:

*Tools:*

- Anaconda3
    - Tested with version: 2020.02

### Activate conda environment
:exclamation: _Optional: Depends on project._ :exclamation:

Change in to root directory and run the commands below:

```sh
# create conda environment. Needed only the first time.
conda env create --file configs/environment.yaml

# if you need to update existing environment
conda env update --file configs/environment.yaml

# activate conda environment
conda activate testing
```

### Steps to run
:exclamation: _Optional: Depends on project._ :exclamation:


Output from this step includes -

```directory
output_directory/
├── parsed_file.tsv               <--- used for model
├── plot.pdf- Plot to visualize data
└── columns.csv - columns before and after filtering step

```

**Note**: The is an example note with a [link](https://github.com/u-brite/team-repo-template).


## Results
:exclamation: _If your project yielded or intends to yield some novel analysis, please include them in your readme. It can be named something other than results as well._ :exclamation:

## Team Members

Priyanka Gupta | pgupta@uabmc.edu | Team Leader  
Shaurita Hutchins | shutchins@uab.edu | Co-leader
