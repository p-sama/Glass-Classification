# Glass-Classification

Task : To classify different samples of glasses based on their physical and chemical properties. Application and comparison of various machine learning classification algorithms and simple demostration of PCA analysis and hyperparameter tuning using GridSearch.

Context : Identification of the glass at a crime scene can prove to be very useful in providing evidence in investigations and forensic purpose. Also, since glasses are used in various industries to manufacture different types of items, identifying the type beforehand from its components (oxide content) can save cost, time and effort.

The dataset is commonly used to demonstrate Machine learning classification algorithms in academic settings. It is available on the UCI Machine Learning repository (See Reference for link).

It contains 214 samples of glasses which can be categorized into different types based on their usage. The original dataset had 7 types but the sample obtained from UCI does not have one which is the vehicle windows float processed (type 4).

The columns in this dataset are:


RI: refractive index

Na: Sodium

Mg: Magnesium

Al: Aluminum

Si: Silica

K: Potassium

Ca: Calcium

Ba: Barium

Fe: Iron

Type of glass (Target label)

RI is an index vaiable and has no units. Columns 3-9 are measured as weight percent in corresponding oxide.

The Target label, Type of Glass has 6 classes:


1: building_windows_float_processed

2: building_windows_non_float_processed

3: vehicle_windows_float_processed

5: containers

6: tableware

7: headlamps
