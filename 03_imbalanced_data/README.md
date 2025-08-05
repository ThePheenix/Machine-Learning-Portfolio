Imbalanced data handling

This is a brief preview of all the methods I will use in this chapter and the purpose of each one.
There are undersampling, oversampling and combined methods.

Undersampling strategies:

RUS: Random undersampling delets randomly data from the majority
CNN: KNN that predicts exactly one majority observation vs. all minorities. This ends in a dataset, that consists of wrong predicted majorities and all minorities.
TomekLinks: finds majority-observations with a minoritie-neighbour and deletes that majority-observation
OSS: OneSidedSelection is like CNN but delets the TomekLinks at the end.

ENN, RENN, ALLKN, NCL: These undersampling strategies cleans the boarder between all classes
