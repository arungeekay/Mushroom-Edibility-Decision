# Mushroom-Edibility-Decision


![image](https://images.pexels.com/photos/168140/pexels-photo-168140.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)

# Inspiration <img src="https://user-images.githubusercontent.com/72274851/222214323-923a3fe7-56e9-4ba0-abff-162681500702.png" width="60" height="60"> 
Machine learning has revolutionized the way we approach problems and has opened up new possibilities for solving complex issues. One such problem is the detection of edible mushrooms by analysing their physical charecteristics. 


# What it does  <img src="https://user-images.githubusercontent.com/72274851/222214323-923a3fe7-56e9-4ba0-abff-162681500702.png" width="60" height="60">  

This project involves identifying edible mushrooms using various features such as cap shape, cap color, gill size, spore print color, habitat, and other characteristics. Machine learning models such as logistic regression, decision trees, random forest, SVM, and XGBoost can be used to build prediction models to classify mushrooms as either edible or poisonous based on these features. The accuracy of each model can be compared to identify the best performing model.

## How i made it <img src="https://user-images.githubusercontent.com/72274851/222215141-6ced575e-414b-4088-bd99-d78921f80f66.png" width="60" height="60"> 

✅ The dataset used in this project is the Mushroom Dataset by ULRIK THYGE PEDERSEN. !
✅ It contains 8124 entries of mushrooms and their physical charecteristics with edible or poisonous label.!
✅ Use a heatmap to analyse co-relation!![image](https://user-images.githubusercontent.com/114347910/222526078-9a088f08-47dc-4ba7-b09e-59730ec272f4.png)!
✅ Analyse relations between other charecteristics and edibility ![image](https://user-images.githubusercontent.com/114347910/222526329-a25c770f-439e-4919-995b-adf57db14dcb.png)
![image](https://user-images.githubusercontent.com/114347910/222526373-26608b87-02d7-4440-9009-2ac0d4a61390.png)
![image](https://user-images.githubusercontent.com/114347910/222526425-807ec884-68f7-4b23-91b6-3792fe6b6518.png)


✅ Used model using intel oneAPI 

![image](https://user-images.githubusercontent.com/72274851/218504609-585bcebe-5101-4477-bdd2-3a1ba13a64a8.png)

Building application using intel oneDAL:The Intel oneAPI Data Analytics Library (oneDAL) contributes to the acceleration of big data analysis by providing highly optimised algorithmic building blocks for all phases of data analytics (preprocessing, transformation, analysis, modelling, validation, and decision making) in batch, online, and distributed processing modes of computation.The library optimizes data ingestion along with algorithmic computation to increase throughput and scalability.

✅ The result is as shown
![image](https://user-images.githubusercontent.com/114347910/222525776-79cd27bc-86d8-4d3f-98f4-b441a5983d7e.png)


## Dependencies <img src="https://user-images.githubusercontent.com/72274851/222215296-64d3a566-02c2-4ff9-9b8f-9ec5096f5799.png" width="60" height="60"> 
This project requires the following dependencies:

✅ Python 3.7 or higher

✅ Scikit-learn

✅ XGBoost

✅ Pandas

✅ NumPy

✅ Matplotlib

✅ Seaborn

# Usage <img src="https://user-images.githubusercontent.com/72274851/222215440-158ffdc1-8a23-4c7f-81c2-44e864d6d043.png" width="60" height="60"> 

To run the project, follow these steps:

- [x] Clone this repository to your local machine.
- [x] Install the dependencies listed above.
- [x] Open a terminal and navigate to the project directory.
- [x] Run the fake_currency_detection.ipynb Jupyter notebook to train and evaluate the machine learning model.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
