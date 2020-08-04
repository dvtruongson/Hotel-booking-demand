    # Hotel-booking-demand

Hotel Booking Demand Datasets: Nuno Antonio, Ana Almeida, Luis Nunes, Data in Brief, 2019.
Data was downloaded from: https://www.sciencedirect.com/science/article/pii/S2352340918315191 and cleaned by Thomas Mock and Antoine Bichat.

    Content

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

All personally identifying information has been removed from the data.

    Acknowledgements

The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

Because I have many classes(3 classes), this problem is an instance of multiclass classification; and because each data point should be classified into only one category, the problem is more specifically an instance of single-label, multiclass classification.

I usually need to do quite a bit of preprocessing on the raw data in order to be able to feed it—as tensors—into a neural network.

Stacks of Dense layers with relu activations can solve a wide range of problems. In a multiclass classification problem (many output classes).

The rmsprop optimizer is generally a good enough choice, whatever the problem. 

As they get better on their training data, neural networks eventually start overfitting and end up obtaining increasingly worse results on data they’venever seen before. 

Be sure to always monitor performance on data that is outside of the training set.

