# Gene_Chip_Ananysis
SJTU CS410 Project

## Dataset
* features: `output/data/dataset_train.npy dataset_test.npy (3558 * num_of_features)`
* labels: `output/data/target_train.npy dataset_test.npy (3558 * 1)`

## LR

using 1 fc-layer.

## SVM

using 1 fc-layer and hinge loss.

## NN

using several fc-layers and crossentropy loss.

## Current accuracy (About 10-30 epochs)
* LR: 88% (with l2 norm) 87% (without norm)
* SVM: 89%
* NN: 91% (with l2 norm, dropout(0.5), relu activation funciton)

Results could be improved with some more parameters adjustment.
