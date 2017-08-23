# Cats vs dogs redux Kaggle submission
[Kaggle cats vs dogs image recognition machine learning competition](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition) (using deep learning).

[Cats vs Dogs - attempt I.pynb](https://github.com/DanGolding/kaggle_cats_vs_dogs_redux/blob/master/Cats%20vs%20Dogs%20-%20attempt%20I.ipynb) achieved a score of 0.09907 on the kaggle competition which would have placed it 426/1315 i.e. in the top third.

Note this code assumes the competition data is stored in a folder called `data/`. The data can be downloaded using the `kaggle_cli` as follows:

    pip install kaggle-cli
    kg config -g -u `username` -p `password` -c dogs-vs-cats-redux-kernels-edition
    kg download

It's worth noting that if you have special characters such as $ in your password you should enclose your pass word in single quotes.

Then put the three downloaded files in a folder called `data/` and unzip the data

    unzip train.zip
    unzip test.zip

Move the `test` data into a subfolder called `data/test/test`, i.e. create one extra subfolder inside `data/test`.

The code will then structure the data files appropriately from there.
