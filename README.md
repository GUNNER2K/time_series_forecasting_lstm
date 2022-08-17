# time_series_forecasting_lstm
### overview 
This repo contains a timeseries project taken from kaggle through the link :https://www.kaggle.com/competitions/competitive-data-science-predict-future-sales
This is a quite challenging project and requires the skills of good data preprocessing . lstm deep learning technique is used to make the forecasting predictions.
The approach taken in this project is quite unique and instead of doing it in traditional way ( converting date column into datetime object and then feeding it to an algorithm ) the data frame is converted into something like this 
![image](https://user-images.githubusercontent.com/95174361/185153717-adddbe5a-13b4-44b1-9bef-f39c56341fb1.png)
and then used lstm on this.

### some insight of visualization 
training loss:

![image](https://user-images.githubusercontent.com/95174361/185153856-86693219-72e1-47a3-a2e8-f8d308d17682.png)

training loss of different models:

![image](https://user-images.githubusercontent.com/95174361/185154065-5e6ac751-b65e-4468-be37-77c9c20f991c.png)

