# Algae Bloom
Understanding Algae growth with regression modeling.

The data set comes from Kaggle, and it is on algae growth of European rivers. The data set shows algae and algae related variables across seasons and river sizes. The seasons are from the autumn, winter, spring, and summer. The dataset also includes the speed of the river, max pH value, minimum O2 level, average chloride level, average value of ammonium, average value of orthophosphate average chlorophyll levels, and average phosphate levels. One of the main motivations for this project is that chemical monitoring is cheap and automated, while biological analysis of samples to identify algae present in water involves microscopic examination, requires labor- of skilled labour, and is therefore both costly and slow. As such, obtaining models that can accurately predict algal frequencies based on chemical properties would facilitate the creation of inexpensive and automated systems to monitor harmful algal blooms.

https://www.kaggle.com/datasets/adoumtaiga/erudit-dataset/data


Takeaways:

Some things to note, excluding the other instances of algae population other than a1 improves the model performance as the algae populations are correlated highly with each other, in turn we would remove them from the model. Random Forest Regressor having the highest R^2 value is not a surprise due to it being an ensemble decision tree based model, it was bound to be more accurate than the decision tree regressor. I think next time I’d like to try an x-boost model to see how it performs especially when I hyper-parameter tune some values such as learning rate, max depth, number of estimators, etc.
