### Building a Neural Network from scratch
>_You gain more understanding of neural networks (and machine learning) when you build one from scratch._

This project contains a neural network built with only NumPy. The notebook shows how the network is trained on a sample [dataset](https://www.kaggle.com/kumargh/pimaindiansdiabetescsv), a csv file that describes the medical records for Pima Indians and whether or not each patient will have an onset of diabetes within five years.

This is a Supervised Machine Learning Problem, a Classification problem.
___
**Number of records:** `768`  
**Number of features:** `8`  
**Numbe of Classes:** `1`  
**Features include:**
- `preg` - Number of times pregnant
- `plas` - Plasma glucose concentration a 2 hours in an oral glucose tolerance test
- `pres` - Diastolic blood pressure (mm Hg)
- `skin` - Triceps skin fold thickness (mm)
- `test` - 2-Hour serum insulin (mu U/ml)
- `mass` - Body mass index (weight in kg/(height in m)^2)
- `pedi` - Diabetes pedigree function
- `age` - Age (years)
**And the target class**
- `class` - Class variable (`1`:tested positive for diabetes, `0`: tested negative for diabetes)

___

#### Installation/Setup
This project requires the following dependencies:
- Python3
- Jupyter
- Numpy