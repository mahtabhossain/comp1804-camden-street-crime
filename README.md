Exploratory Data Analysis (EDA) on the Camden Street Crime Dataset.
------------------------------
We used the downloaded dataset from the London Borough of Camden link which had data upto Aug, 2019. We also retrieved additional recent data through the Police API. The final EDA is conducted using the combined dataset [Jan, 2015 - Dec, 2020].  There are plenty of explanatory data analysis that can be conducted - we approached it in the following three ways:

1. We first perform an initial data analysis on all the street crimes over different years and category of crimes.
2. Subsequently, we perform street crimes' outcome analysis (e.g., average duration of days for each crime, proportion of resolved cases, etc.) on the dataset.
3. Finally, we inspect a specific crime (e.g., violence and sexual offences) across different Wards (neighbourhoods) within London Borough of Camden, and try to have an indication of whether this is likely to occur in one particular Ward (neighbourhood) compared to the remaining ones using statistical techniques.

The main exploratory data analysis notebook is: EDA_camden_street_crime.ipynb.
The additional data retrieval notebook is: data_collection_camden_street_crime.ipynb.

Furthermore, we have two extra notebooks - i) one (verify_police_api_and_camden_stored_dataset.ipynb) is used for validating a sample between the downloaded dataset version and the Police API retrieved one, and ii) the other (modelling_and_inference_camden_street_crime.ipynb) to just demonstrate a simple modelling/inference exercise on this dataset.
