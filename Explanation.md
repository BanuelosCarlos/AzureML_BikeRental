# Steps to try to predict 
Firts we create a Resource Group in Azure Porta, the we create a Work Space in Azule ML, it is here where we go to the Manage section an we select Compute. 
![Bike Prediction](Bike%20Prediction/2022-06-10%20(1).png)\
\
For this Model, we give the name, and selcect CPU VM type, and the Standar_DS12_v2, and click in create. 

![Bike Prediction](Bike%20Prediction/2022-06-10%20(2).png)\
\
Click on Data in Assets section we select create

![Bike Prediction](Bike%20Prediction/2022-06-10%20(3).png)\
\
now we select "From Web Files".

![Bike Prediction](Bike%20Prediction/2022-06-10%20(4).png)\
\
In the new window we srite the web adress to load the data, we name it, Select tabulat data type and add some description.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(5).png)\
\
The data is loaded.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(6).png)\
\
We need to confirm details.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(7).png)\
\
The data set is created successfuly.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(8).png)\
\
Now Author section we select Automated ML.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(9).png)\
\
We create a new Automated ML job, we give name for the experiment, select the Target column, the cluster that we created previously and we go next

![Bike Prediction](Bike%20Prediction/2022-06-10%20(10).png)\
\
We confirm the detail for the Model with the type of task and we put the model in training.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(11).png)\
\
We go to Assets section and select Jobs here we will see when the Model is trained.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(19).png)\
\
Now that the model is trained we can do predictions

![Bike Prediction](Bike%20Prediction/2022-06-10%20(20).png)\
\
In the model tab in Jobs we select deploy

![Bike Prediction](Bike%20Prediction/2022-06-10%20(21).png)\
\
Now for the predictions we need to go to Endpoint in the Assets section, i used the Python languaje 

![Bike Prediction](Bike%20Prediction/2022-06-10%20(22).png)\
\
We replace the API key for this web service and finnaly we write de data to predict with the model, we run the script and the model will return the prediction.

![Bike Prediction](Bike%20Prediction/2022-06-10%20(23).png )\
\





