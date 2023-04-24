## Usage Requirements and Limitations

The main use of this is to convert the student quiz and survey data into a more acceptable format for more universal usage. This is a document, detailing the limitations of this software.

### Usage Requirements

General usage requirements of this software.

- **Two CSVs for quiz processing**: to process student quiz data we must have two different csv forms in order to correctly run the code. The csv names will be `<QUIZ_NAME>_ Attempt Details` and `<QUIZ_NAME>_ Question Details`. These can be downloaded on D2L. Attempt Details will be found in Grades under the carrot next to the quiz you want details on. Question Details will be found in the Question Details Tab on View Statistics. View Statistics can be accessed in the carrot next to the quiz you want details on.

- **One CSV for survey processing**: to process survey data only one csv is required. In order to get the csv the survey must be set up with reports before taking the survey. To do so you just select Add Report when creating a survey. The report can be given any name, but the report type must be individual attempts and you need to release reports to desired D2L roles. In order to process surveys the Report must be downloaded. It can be downloaded by selecting Reports in the carrot next to the survey you would like processed.

- **Python**: Python must be installed. Python can be installed through python.org.

- **Pandas**: Pandas must be installed

- **Numpy**: Numpy must be installed

- **Optional - Additional Packages**: For extra functionality, like visualization, more packages may be required.

- **Optional - Jupyter**: For easier usage, it is possible to simply run a jupyter notebook that has an interactable interface. Follow anaconda installation instructions for more details.

### Limitations

Limitations of the software.

- **Cannot Process Matching Questions for Quiz**: Unfortunately for matching type quiz questions we will not correctly process the data regarding what a student has selected. However, the scoring for the question will be done correctly.

- **Temporarily No Library Or GUI**: At the moment, this feature cannot be accessed through methods other than installing ipynb or  py file.




