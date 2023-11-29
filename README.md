# deep-learning-challenge
_Bootcamp: UPENN-VIRT-DATA-PT-06-2023-U-LOLC-MTTH Module 21 Challenge: Deep Learning_

## About the Project
### Challenge background description:
> The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.
>
> From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:
>
> - EIN and NAME—Identification columns
> - APPLICATION_TYPE—Alphabet Soup application type
> - AFFILIATION—Affiliated sector of industry
> - CLASSIFICATION—Government organization classification
> - USE_CASE—Use case for funding
> - ORGANIZATION—Organization type
> - STATUS—Active status
> - INCOME_AMT—Income classification
> - SPECIAL_CONSIDERATIONS—Special considerations for application
> - ASK_AMT—Funding amount requested
> - IS_SUCCESSFUL—Was the money used effectively

### Analysis
A full analysis may be found in [analysis.md](analysis.md).
The result of the exercise is a model (optimized) with a 0.7342 accuracy that can be used to help assess whether an applicant is a good candidate for receiving funding from the charity Alphabet Soup.

## About the Models
### Requirements
Clone this repo: `git clone https://github.com/4a6166/deep-learning-challenge.git`

All three Jupyter Notebook files were run using Google Colab.
All output compiling, training, evaluation, and generation of outputs was done on the cloud platfrom.

### Output
There are two output files resulting from this exercise, both in HDF5 format.
These files are the trained models that were generated during the exercise.
Both may be found in the `output` folder of this repo.

`AlphabetSoupCharity.h5` contains the output for the Compile, Train and Evaluate Model.
It should have a accuracy of 0.7307 and a loss of 0.5646.

`AlphabetSoupCharity_Optimization.h5` contains the output for the Optimized Model.
It should have an accuracy of 0.7342 and a loss of 0.6275.

There is no output file for the Tuned Model.
It did not finish running before Google cut me off from free compute resources (6ish hours).

## Credits
IRS. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/ Links to an external site.

## License
[MIT License](LICENSE)
