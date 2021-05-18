# 684_Final
Document Classification: Author identification

The report fulfilling the requirements of `final.pdf` can be found in `report.pdf`.

The code in `Code.ipynb` implements the methods described in the paper using the data in C50. The code is ordered and labeled as per `report.pdf`. Results from running the code are displayed for convenience. Total runtime would be around an hour.

The code in `50_authors.ipynb` applies the neural network solution to the 50-class classification problem, for a train-test split of 9-1. This is not the focus of the paper, but used as a baseline for comparison. Results from running the code are displayed for convenience. Total runtime would be around an hour.

If there are errors thrown in the first code block, try removing the following line in both notebooks:

authors.remove(".DS_Store")