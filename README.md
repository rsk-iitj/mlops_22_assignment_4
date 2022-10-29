# Please Edit the ReadMe File to View it in Proper Format


                  Classifier  train_accuracy  dev_accuracy  test_accuracy
0     SVC(C=0.1, gamma=0.01)        0.112245      0.072222       0.089054
1     SVC(C=0.2, gamma=0.01)        0.112245      0.072222       0.089054
2     SVC(C=0.5, gamma=0.01)        0.896104      0.150000       0.155844
3     SVC(C=0.6, gamma=0.01)        1.000000      0.205556       0.196660
4       SVC(C=1, gamma=0.01)        1.000000      0.638889       0.645640
5       SVC(C=2, gamma=0.01)        1.000000      0.661111       0.680891
6       SVC(C=5, gamma=0.01)        1.000000      0.661111       0.680891
7       SVC(C=7, gamma=0.01)        1.000000      0.661111       0.680891
8      SVC(C=10, gamma=0.01)        1.000000      0.661111       0.680891
9    SVC(C=0.1, gamma=0.005)        0.148423      0.094444       0.105751
10   SVC(C=0.2, gamma=0.005)        0.509276      0.322222       0.335807
11   SVC(C=0.5, gamma=0.005)        1.000000      0.905556       0.903525
12   SVC(C=0.6, gamma=0.005)        1.000000      0.927778       0.942486
13     SVC(C=1, gamma=0.005)        1.000000      0.977778       0.970315
14     SVC(C=2, gamma=0.005)        1.000000      0.977778       0.970315
15     SVC(C=5, gamma=0.005)        1.000000      0.977778       0.970315
16     SVC(C=7, gamma=0.005)        1.000000      0.977778       0.970315
17    SVC(C=10, gamma=0.005)        1.000000      0.977778       0.970315
18   SVC(C=0.1, gamma=0.001)        0.970315      0.961111       0.966605
19   SVC(C=0.2, gamma=0.001)        0.981447      0.977778       0.987013
20   SVC(C=0.5, gamma=0.001)        0.997217      1.000000       0.988868
21   SVC(C=0.6, gamma=0.001)        0.997217      1.000000       0.988868
22     SVC(C=1, gamma=0.001)        1.000000      1.000000       0.990724
23     SVC(C=2, gamma=0.001)        1.000000      1.000000       0.988868
24     SVC(C=5, gamma=0.001)        1.000000      1.000000       0.988868
25     SVC(C=7, gamma=0.001)        1.000000      1.000000       0.988868
26    SVC(C=10, gamma=0.001)        1.000000      1.000000       0.988868
27  SVC(C=0.1, gamma=0.0005)        0.952690      0.961111       0.959184
28  SVC(C=0.2, gamma=0.0005)        0.974026      0.977778       0.974026
29  SVC(C=0.5, gamma=0.0005)        0.990724      0.988889       0.987013
30  SVC(C=0.6, gamma=0.0005)        0.990724      0.994444       0.987013
31    SVC(C=1, gamma=0.0005)        0.997217      1.000000       0.988868
32    SVC(C=2, gamma=0.0005)        0.999072      1.000000       0.987013
33    SVC(C=5, gamma=0.0005)        1.000000      1.000000       0.988868
34    SVC(C=7, gamma=0.0005)        1.000000      1.000000       0.988868
35   SVC(C=10, gamma=0.0005)        1.000000      1.000000       0.988868
36  SVC(C=0.1, gamma=0.0001)        0.868275      0.861111       0.849722
37  SVC(C=0.2, gamma=0.0001)        0.929499      0.955556       0.931354
38  SVC(C=0.5, gamma=0.0001)        0.960111      0.961111       0.961039
39  SVC(C=0.6, gamma=0.0001)        0.964750      0.966667       0.962894
40    SVC(C=1, gamma=0.0001)        0.974026      0.983333       0.974026
41    SVC(C=2, gamma=0.0001)        0.982375      0.994444       0.987013
42    SVC(C=5, gamma=0.0001)        0.995362      0.994444       0.988868
43    SVC(C=7, gamma=0.0001)        0.996289      0.994444       0.987013
44   SVC(C=10, gamma=0.0001)        0.997217      0.994444       0.987013

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.112245      1.000000       0.917708
1    Dev Set      0.072222      1.000000       0.833086
2   Test Set      0.089054      0.990724       0.831004

Best Classification Train Accuracy for classifier SVC(C=0.6, gamma=0.01) is 1.00

Best Classification Dev Accuracy for classifier SVC(C=0.5, gamma=0.001) is 1.00

Best Classification Test Accuracy for classifier SVC(C=1, gamma=0.001) is 0.99


Classification report for classifier SVC(C=1, gamma=0.001):
              precision    recall  f1-score   support

           0       1.00      0.98      0.99        65
           1       0.97      1.00      0.98        63
           2       1.00      1.00      1.00        53
           3       1.00      1.00      1.00        46
           4       0.98      0.98      0.98        48
           5       1.00      0.98      0.99        48
           6       1.00      1.00      1.00        53
           7       0.98      0.98      0.98        57
           8       1.00      0.94      0.97        51
           9       0.95      1.00      0.97        55

    accuracy                           0.99       539
   macro avg       0.99      0.99      0.99       539
weighted avg       0.99      0.99      0.99       539


Confusion report for classifier SVC(C=1, gamma=0.001):
[[64  0  0  0  1  0  0  0  0  0]
 [ 0 63  0  0  0  0  0  0  0  0]
 [ 0  0 53  0  0  0  0  0  0  0]
 [ 0  0  0 46  0  0  0  0  0  0]
 [ 0  0  0  0 47  0  0  0  0  1]
 [ 0  0  0  0  0 47  0  0  0  1]
 [ 0  0  0  0  0  0 53  0  0  0]
 [ 0  0  0  0  0  0  0 56  0  1]
 [ 0  2  0  0  0  0  0  1 48  0]
 [ 0  0  0  0  0  0  0  0  0 55]]

                                                           Classifier  train_accuracy  dev_accuracy  test_accuracy
0                                            DecisionTreeClassifier()        1.000000      0.827778       0.864564
1                         DecisionTreeClassifier(min_samples_split=3)        0.993506      0.838889       0.860853
2                         DecisionTreeClassifier(min_samples_split=5)        0.975881      0.811111       0.864564
3                        DecisionTreeClassifier(min_samples_split=10)        0.944341      0.783333       0.834879
4                          DecisionTreeClassifier(min_samples_leaf=3)        0.952690      0.811111       0.849722
5     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=3)        0.952690      0.811111       0.846011
6     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=5)        0.952690      0.805556       0.849722
7    DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=10)        0.934137      0.811111       0.840445
8                          DecisionTreeClassifier(min_samples_leaf=5)        0.913729      0.766667       0.821892
9     DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=3)        0.914657      0.788889       0.810761
10    DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=5)        0.913729      0.761111       0.816327
11   DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=10)        0.914657      0.777778       0.812616
12                        DecisionTreeClassifier(min_samples_leaf=10)        0.864564      0.777778       0.810761
13   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=3)        0.864564      0.777778       0.810761
14   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=5)        0.864564      0.777778       0.810761
15  DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=10)        0.864564      0.777778       0.810761

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.864564      1.000000       0.926310
1    Dev Set      0.761111      0.838889       0.794097
2   Test Set      0.810761      0.864564       0.832212

Best Classification Train Accuracy for classifier DecisionTreeClassifier() is 1.00

Best Classification Dev Accuracy for classifier DecisionTreeClassifier(min_samples_split=3) is 0.84

Best Classification Test Accuracy for classifier DecisionTreeClassifier() is 0.86


Classification report for classifier DecisionTreeClassifier():
              precision    recall  f1-score   support

           0       0.98      0.94      0.96        52
           1       0.68      0.81      0.74        53
           2       0.80      0.86      0.83        56
           3       0.83      0.78      0.81        51
           4       0.78      0.74      0.76        57
           5       0.85      0.85      0.85        62
           6       0.83      0.72      0.77        54
           7       0.91      0.82      0.86        60
           8       0.79      0.67      0.73        49
           9       0.69      0.91      0.79        45

    accuracy                           0.81       539
   macro avg       0.81      0.81      0.81       539
weighted avg       0.82      0.81      0.81       539


Confusion report for classifier DecisionTreeClassifier():
[[49  0  0  0  1  0  0  1  0  1]
 [ 0 43  1  1  1  1  2  0  1  3]
 [ 0  5 48  1  0  0  1  0  0  1]
 [ 0  3  1 40  0  0  0  0  4  3]
 [ 1  1  3  1 42  1  0  4  2  2]
 [ 0  0  3  0  5 53  0  0  0  1]
 [ 0  6  2  0  0  6 39  0  1  0]
 [ 0  1  0  1  4  0  0 49  0  5]
 [ 0  4  2  2  0  1  5  0 33  2]
 [ 0  0  0  2  1  0  0  0  1 41]]

                  Classifier  train_accuracy  dev_accuracy  test_accuracy
0     SVC(C=0.1, gamma=0.01)        0.117295      0.074074       0.070218
1     SVC(C=0.2, gamma=0.01)        0.119007      0.074074       0.070218
2     SVC(C=0.5, gamma=0.01)        0.820205      0.129630       0.152542
3     SVC(C=0.6, gamma=0.01)        1.000000      0.162037       0.208232
4       SVC(C=1, gamma=0.01)        1.000000      0.532407       0.634383
5       SVC(C=2, gamma=0.01)        1.000000      0.578704       0.682809
6       SVC(C=5, gamma=0.01)        1.000000      0.578704       0.682809
7       SVC(C=7, gamma=0.01)        1.000000      0.578704       0.682809
8      SVC(C=10, gamma=0.01)        1.000000      0.578704       0.682809
9    SVC(C=0.1, gamma=0.005)        0.155822      0.101852       0.106538
10   SVC(C=0.2, gamma=0.005)        0.518836      0.319444       0.365617
11   SVC(C=0.5, gamma=0.005)        1.000000      0.884259       0.924939
12   SVC(C=0.6, gamma=0.005)        1.000000      0.898148       0.949153
13     SVC(C=1, gamma=0.005)        1.000000      0.958333       0.961259
14     SVC(C=2, gamma=0.005)        1.000000      0.972222       0.963680
15     SVC(C=5, gamma=0.005)        1.000000      0.972222       0.963680
16     SVC(C=7, gamma=0.005)        1.000000      0.972222       0.963680
17    SVC(C=10, gamma=0.005)        1.000000      0.972222       0.963680
18   SVC(C=0.1, gamma=0.001)        0.968322      0.935185       0.966102
19   SVC(C=0.2, gamma=0.001)        0.983733      0.976852       0.978208
20   SVC(C=0.5, gamma=0.001)        0.993151      0.990741       0.990315
21   SVC(C=0.6, gamma=0.001)        0.995719      0.995370       0.990315
22     SVC(C=1, gamma=0.001)        0.998288      0.995370       0.992736
23     SVC(C=2, gamma=0.001)        1.000000      1.000000       0.995157
24     SVC(C=5, gamma=0.001)        1.000000      1.000000       0.995157
25     SVC(C=7, gamma=0.001)        1.000000      1.000000       0.995157
26    SVC(C=10, gamma=0.001)        1.000000      1.000000       0.995157
27  SVC(C=0.1, gamma=0.0005)        0.961473      0.944444       0.958838
28  SVC(C=0.2, gamma=0.0005)        0.978596      0.962963       0.970944
29  SVC(C=0.5, gamma=0.0005)        0.988014      0.981481       0.985472
30  SVC(C=0.6, gamma=0.0005)        0.988870      0.986111       0.987893
31    SVC(C=1, gamma=0.0005)        0.993151      0.995370       0.990315
32    SVC(C=2, gamma=0.0005)        0.997432      1.000000       0.995157
33    SVC(C=5, gamma=0.0005)        1.000000      1.000000       0.997579
34    SVC(C=7, gamma=0.0005)        1.000000      1.000000       0.997579
35   SVC(C=10, gamma=0.0005)        1.000000      1.000000       0.997579
36  SVC(C=0.1, gamma=0.0001)        0.890411      0.898148       0.903148
37  SVC(C=0.2, gamma=0.0001)        0.943493      0.925926       0.941889
38  SVC(C=0.5, gamma=0.0001)        0.964041      0.949074       0.956416
39  SVC(C=0.6, gamma=0.0001)        0.970890      0.949074       0.961259
40    SVC(C=1, gamma=0.0001)        0.977740      0.962963       0.973366
41    SVC(C=2, gamma=0.0001)        0.982877      0.981481       0.978208
42    SVC(C=5, gamma=0.0001)        0.992295      0.995370       0.990315
43    SVC(C=7, gamma=0.0001)        0.993151      0.995370       0.992736
44   SVC(C=10, gamma=0.0001)        0.994007      0.995370       0.992736

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.117295      1.000000       0.917485
1    Dev Set      0.074074      1.000000       0.816770
2   Test Set      0.070218      0.997579       0.833306

Best Classification Train Accuracy for classifier SVC(C=0.6, gamma=0.01) is 1.00

Best Classification Dev Accuracy for classifier SVC(C=2, gamma=0.001) is 1.00

Best Classification Test Accuracy for classifier SVC(C=5, gamma=0.0005) is 1.00


Classification report for classifier SVC(C=5, gamma=0.0005):
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        41
           1       1.00      1.00      1.00        50
           2       1.00      1.00      1.00        48
           3       1.00      1.00      1.00        44
           4       0.97      0.97      0.97        33
           5       0.97      1.00      0.98        29
           6       1.00      1.00      1.00        46
           7       1.00      0.98      0.99        46
           8       1.00      1.00      1.00        30
           9       0.98      0.98      0.98        46

    accuracy                           0.99       413
   macro avg       0.99      0.99      0.99       413
weighted avg       0.99      0.99      0.99       413


Confusion report for classifier SVC(C=5, gamma=0.0005):
[[41  0  0  0  0  0  0  0  0  0]
 [ 0 50  0  0  0  0  0  0  0  0]
 [ 0  0 48  0  0  0  0  0  0  0]
 [ 0  0  0 44  0  0  0  0  0  0]
 [ 0  0  0  0 32  0  0  0  0  1]
 [ 0  0  0  0  0 29  0  0  0  0]
 [ 0  0  0  0  0  0 46  0  0  0]
 [ 0  0  0  0  1  0  0 45  0  0]
 [ 0  0  0  0  0  0  0  0 30  0]
 [ 0  0  0  0  0  1  0  0  0 45]]

                                                           Classifier  train_accuracy  dev_accuracy  test_accuracy
0                                            DecisionTreeClassifier()        1.000000      0.847222       0.847458
1                         DecisionTreeClassifier(min_samples_split=3)        0.984589      0.814815       0.847458
2                         DecisionTreeClassifier(min_samples_split=5)        0.967466      0.819444       0.849879
3                        DecisionTreeClassifier(min_samples_split=10)        0.940925      0.814815       0.820823
4                          DecisionTreeClassifier(min_samples_leaf=3)        0.942637      0.810185       0.832930
5     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=3)        0.942637      0.800926       0.832930
6     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=5)        0.942637      0.814815       0.825666
7    DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=10)        0.924658      0.819444       0.825666
8                          DecisionTreeClassifier(min_samples_leaf=5)        0.915240      0.833333       0.811138
9     DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=3)        0.915240      0.828704       0.808717
10    DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=5)        0.915240      0.824074       0.818402
11   DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=10)        0.915240      0.819444       0.818402
12                        DecisionTreeClassifier(min_samples_leaf=10)        0.871575      0.787037       0.815981
13   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=3)        0.871575      0.782407       0.811138
14   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=5)        0.871575      0.796296       0.818402
15  DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=10)        0.871575      0.787037       0.815981

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.871575      1.000000       0.924551
1    Dev Set      0.782407      0.847222       0.812500
2   Test Set      0.808717      0.849879       0.825061

Best Classification Train Accuracy for classifier DecisionTreeClassifier() is 1.00

Best Classification Dev Accuracy for classifier DecisionTreeClassifier() is 0.85

Best Classification Test Accuracy for classifier DecisionTreeClassifier(min_samples_split=5) is 0.85


Classification report for classifier DecisionTreeClassifier(min_samples_split=5):
              precision    recall  f1-score   support

           0       0.95      1.00      0.97        37
           1       0.73      0.93      0.81        40
           2       0.87      0.85      0.86        39
           3       0.61      0.81      0.70        43
           4       0.85      0.76      0.80        45
           5       0.84      0.89      0.87        47
           6       1.00      0.89      0.94        36
           7       0.95      0.82      0.88        44
           8       0.75      0.57      0.65        37
           9       0.75      0.67      0.71        45

    accuracy                           0.82       413
   macro avg       0.83      0.82      0.82       413
weighted avg       0.83      0.82      0.82       413


Confusion report for classifier DecisionTreeClassifier(min_samples_split=5):
[[37  0  0  0  0  0  0  0  0  0]
 [ 0 37  0  1  0  0  0  0  1  1]
 [ 0  1 33  2  0  2  0  0  1  0]
 [ 0  2  1 35  1  0  0  2  1  1]
 [ 0  4  0  0 34  3  0  0  2  2]
 [ 0  1  0  0  2 42  0  0  0  2]
 [ 0  1  1  0  0  2 32  0  0  0]
 [ 0  0  2  3  0  1  0 36  1  1]
 [ 0  3  1  8  1  0  0  0 21  3]
 [ 2  2  0  8  2  0  0  0  1 30]]

                  Classifier  train_accuracy  dev_accuracy  test_accuracy
0     SVC(C=0.1, gamma=0.01)        0.213206      0.102564       0.120915
1     SVC(C=0.2, gamma=0.01)        0.218775      0.102564       0.120915
2     SVC(C=0.5, gamma=0.01)        0.996818      0.196581       0.199346
3     SVC(C=0.6, gamma=0.01)        1.000000      0.252137       0.245098
4       SVC(C=1, gamma=0.01)        1.000000      0.747863       0.640523
5       SVC(C=2, gamma=0.01)        1.000000      0.764957       0.666667
6       SVC(C=5, gamma=0.01)        1.000000      0.764957       0.666667
7       SVC(C=7, gamma=0.01)        1.000000      0.764957       0.666667
8      SVC(C=10, gamma=0.01)        1.000000      0.764957       0.666667
9    SVC(C=0.1, gamma=0.005)        0.314240      0.247863       0.205882
10   SVC(C=0.2, gamma=0.005)        0.705648      0.491453       0.379085
11   SVC(C=0.5, gamma=0.005)        1.000000      0.918803       0.885621
12   SVC(C=0.6, gamma=0.005)        1.000000      0.931624       0.915033
13     SVC(C=1, gamma=0.005)        1.000000      0.957265       0.947712
14     SVC(C=2, gamma=0.005)        1.000000      0.961538       0.950980
15     SVC(C=5, gamma=0.005)        1.000000      0.961538       0.950980
16     SVC(C=7, gamma=0.005)        1.000000      0.961538       0.950980
17    SVC(C=10, gamma=0.005)        1.000000      0.961538       0.950980
18   SVC(C=0.1, gamma=0.001)        0.973747      0.970085       0.944444
19   SVC(C=0.2, gamma=0.001)        0.988862      0.978632       0.970588
20   SVC(C=0.5, gamma=0.001)        0.998409      0.982906       0.980392
21   SVC(C=0.6, gamma=0.001)        0.998409      0.982906       0.980392
22     SVC(C=1, gamma=0.001)        0.998409      0.987179       0.986928
23     SVC(C=2, gamma=0.001)        1.000000      0.987179       0.986928
24     SVC(C=5, gamma=0.001)        1.000000      0.987179       0.983660
25     SVC(C=7, gamma=0.001)        1.000000      0.987179       0.983660
26    SVC(C=10, gamma=0.001)        1.000000      0.987179       0.983660
27  SVC(C=0.1, gamma=0.0005)        0.964200      0.957265       0.937908
28  SVC(C=0.2, gamma=0.0005)        0.981702      0.974359       0.954248
29  SVC(C=0.5, gamma=0.0005)        0.992045      0.982906       0.983660
30  SVC(C=0.6, gamma=0.0005)        0.995227      0.982906       0.983660
31    SVC(C=1, gamma=0.0005)        0.998409      0.987179       0.983660
32    SVC(C=2, gamma=0.0005)        0.998409      0.991453       0.986928
33    SVC(C=5, gamma=0.0005)        1.000000      0.991453       0.983660
34    SVC(C=7, gamma=0.0005)        1.000000      0.991453       0.983660
35   SVC(C=10, gamma=0.0005)        1.000000      0.991453       0.983660
36  SVC(C=0.1, gamma=0.0001)        0.881464      0.876068       0.849673
37  SVC(C=0.2, gamma=0.0001)        0.937152      0.944444       0.908497
38  SVC(C=0.5, gamma=0.0001)        0.964996      0.961538       0.937908
39  SVC(C=0.6, gamma=0.0001)        0.969769      0.961538       0.944444
40    SVC(C=1, gamma=0.0001)        0.980111      0.974359       0.954248
41    SVC(C=2, gamma=0.0001)        0.988067      0.978632       0.973856
42    SVC(C=5, gamma=0.0001)        0.996818      0.982906       0.980392
43    SVC(C=7, gamma=0.0001)        0.996818      0.987179       0.980392
44   SVC(C=10, gamma=0.0001)        0.998409      0.982906       0.980392

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.213206      1.000000       0.934447
1    Dev Set      0.102564      0.991453       0.849003
2   Test Set      0.120915      0.986928       0.827160

Best Classification Train Accuracy for classifier SVC(C=0.6, gamma=0.01) is 1.00

Best Classification Dev Accuracy for classifier SVC(C=2, gamma=0.0005) is 0.99

Best Classification Test Accuracy for classifier SVC(C=1, gamma=0.001) is 0.99


Classification report for classifier SVC(C=1, gamma=0.001):
              precision    recall  f1-score   support

           0       0.96      1.00      0.98        24
           1       0.96      1.00      0.98        27
           2       1.00      1.00      1.00        30
           3       1.00      0.98      0.99        41
           4       1.00      1.00      1.00        21
           5       1.00      0.93      0.96        29
           6       1.00      0.97      0.98        33
           7       0.94      1.00      0.97        33
           8       1.00      0.97      0.99        35
           9       0.94      0.97      0.96        33

    accuracy                           0.98       306
   macro avg       0.98      0.98      0.98       306
weighted avg       0.98      0.98      0.98       306


Confusion report for classifier SVC(C=1, gamma=0.001):
[[24  0  0  0  0  0  0  0  0  0]
 [ 0 27  0  0  0  0  0  0  0  0]
 [ 0  0 30  0  0  0  0  0  0  0]
 [ 0  0  0 40  0  0  0  1  0  0]
 [ 0  0  0  0 21  0  0  0  0  0]
 [ 0  0  0  0  0 27  0  0  0  2]
 [ 1  0  0  0  0  0 32  0  0  0]
 [ 0  0  0  0  0  0  0 33  0  0]
 [ 0  1  0  0  0  0  0  0 34  0]
 [ 0  0  0  0  0  0  0  1  0 32]]

                                                           Classifier  train_accuracy  dev_accuracy  test_accuracy
0                                            DecisionTreeClassifier()        1.000000      0.829060       0.859477
1                         DecisionTreeClassifier(min_samples_split=3)        0.986476      0.820513       0.866013
2                         DecisionTreeClassifier(min_samples_split=5)        0.972951      0.820513       0.862745
3                        DecisionTreeClassifier(min_samples_split=10)        0.945903      0.816239       0.856209
4                          DecisionTreeClassifier(min_samples_leaf=3)        0.953858      0.799145       0.859477
5     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=3)        0.953858      0.807692       0.859477
6     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=5)        0.953858      0.807692       0.866013
7    DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=10)        0.938743      0.799145       0.859477
8                          DecisionTreeClassifier(min_samples_leaf=5)        0.929992      0.811966       0.856209
9     DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=3)        0.929992      0.811966       0.862745
10    DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=5)        0.929992      0.799145       0.862745
11   DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=10)        0.929992      0.803419       0.856209
12                        DecisionTreeClassifier(min_samples_leaf=10)        0.864757      0.794872       0.833333
13   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=3)        0.864757      0.794872       0.833333
14   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=5)        0.864757      0.794872       0.833333
15  DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=10)        0.864757      0.790598       0.839869

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.864757      1.000000       0.930290
1    Dev Set      0.790598      0.829060       0.806357
2   Test Set      0.833333      0.866013       0.854167

Best Classification Train Accuracy for classifier DecisionTreeClassifier() is 1.00

Best Classification Dev Accuracy for classifier DecisionTreeClassifier() is 0.83

Best Classification Test Accuracy for classifier DecisionTreeClassifier(min_samples_split=3) is 0.87


Classification report for classifier DecisionTreeClassifier(min_samples_split=3):
              precision    recall  f1-score   support

           0       0.97      0.92      0.95        38
           1       0.78      0.82      0.79        38
           2       0.91      0.81      0.85        36
           3       0.75      0.77      0.76        31
           4       0.81      0.84      0.82        25
           5       0.96      1.00      0.98        24
           6       1.00      1.00      1.00        28
           7       0.82      0.90      0.86        31
           8       0.52      0.65      0.58        17
           9       0.81      0.68      0.74        38

    accuracy                           0.84       306
   macro avg       0.83      0.84      0.83       306
weighted avg       0.85      0.84      0.84       306


Confusion report for classifier DecisionTreeClassifier(min_samples_split=3):
[[35  0  0  0  0  1  0  0  0  2]
 [ 0 31  1  0  1  0  0  1  3  1]
 [ 0  2 29  3  0  0  0  1  0  1]
 [ 0  0  1 24  3  0  0  0  2  1]
 [ 1  1  0  0 21  0  0  2  0  0]
 [ 0  0  0  0  0 24  0  0  0  0]
 [ 0  0  0  0  0  0 28  0  0  0]
 [ 0  1  1  0  1  0  0 28  0  0]
 [ 0  4  0  1  0  0  0  0 11  1]
 [ 0  1  0  4  0  0  0  2  5 26]]

                  Classifier  train_accuracy  dev_accuracy  test_accuracy
0     SVC(C=0.1, gamma=0.01)        0.104677      0.086957       0.081218
1     SVC(C=0.2, gamma=0.01)        0.115813      0.086957       0.081218
2     SVC(C=0.5, gamma=0.01)        0.998515      0.217391       0.289340
3     SVC(C=0.6, gamma=0.01)        1.000000      0.264822       0.350254
4       SVC(C=1, gamma=0.01)        1.000000      0.750988       0.761421
5       SVC(C=2, gamma=0.01)        1.000000      0.782609       0.771574
6       SVC(C=5, gamma=0.01)        1.000000      0.782609       0.771574
7       SVC(C=7, gamma=0.01)        1.000000      0.782609       0.771574
8      SVC(C=10, gamma=0.01)        1.000000      0.782609       0.771574
9    SVC(C=0.1, gamma=0.005)        0.284336      0.201581       0.228426
10   SVC(C=0.2, gamma=0.005)        0.688938      0.478261       0.502538
11   SVC(C=0.5, gamma=0.005)        1.000000      0.897233       0.888325
12   SVC(C=0.6, gamma=0.005)        1.000000      0.924901       0.918782
13     SVC(C=1, gamma=0.005)        1.000000      0.956522       0.949239
14     SVC(C=2, gamma=0.005)        1.000000      0.956522       0.949239
15     SVC(C=5, gamma=0.005)        1.000000      0.956522       0.949239
16     SVC(C=7, gamma=0.005)        1.000000      0.956522       0.949239
17    SVC(C=10, gamma=0.005)        1.000000      0.956522       0.949239
18   SVC(C=0.1, gamma=0.001)        0.974759      0.976285       0.959391
19   SVC(C=0.2, gamma=0.001)        0.986637      0.992095       0.979695
20   SVC(C=0.5, gamma=0.001)        0.996288      0.996047       0.989848
21   SVC(C=0.6, gamma=0.001)        0.997773      0.996047       0.989848
22     SVC(C=1, gamma=0.001)        0.999258      0.996047       0.989848
23     SVC(C=2, gamma=0.001)        1.000000      0.992095       0.989848
24     SVC(C=5, gamma=0.001)        1.000000      0.992095       0.989848
25     SVC(C=7, gamma=0.001)        1.000000      0.992095       0.989848
26    SVC(C=10, gamma=0.001)        1.000000      0.992095       0.989848
27  SVC(C=0.1, gamma=0.0005)        0.967335      0.972332       0.949239
28  SVC(C=0.2, gamma=0.0005)        0.977728      0.980237       0.954315
29  SVC(C=0.5, gamma=0.0005)        0.991834      0.992095       0.984772
30  SVC(C=0.6, gamma=0.0005)        0.994061      0.992095       0.984772
31    SVC(C=1, gamma=0.0005)        0.996288      0.996047       0.989848
32    SVC(C=2, gamma=0.0005)        0.998515      0.992095       0.989848
33    SVC(C=5, gamma=0.0005)        1.000000      0.992095       0.989848
34    SVC(C=7, gamma=0.0005)        1.000000      0.992095       0.989848
35   SVC(C=10, gamma=0.0005)        1.000000      0.992095       0.989848
36  SVC(C=0.1, gamma=0.0001)        0.907201      0.948617       0.903553
37  SVC(C=0.2, gamma=0.0001)        0.943578      0.968379       0.928934
38  SVC(C=0.5, gamma=0.0001)        0.968077      0.976285       0.949239
39  SVC(C=0.6, gamma=0.0001)        0.970304      0.980237       0.954315
40    SVC(C=1, gamma=0.0001)        0.976986      0.980237       0.964467
41    SVC(C=2, gamma=0.0001)        0.985152      0.992095       0.984772
42    SVC(C=5, gamma=0.0001)        0.994061      0.988142       0.989848
43    SVC(C=7, gamma=0.0001)        0.995546      0.988142       0.989848
44   SVC(C=10, gamma=0.0001)        0.998515      0.988142       0.989848

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.104677      1.000000       0.929159
1    Dev Set      0.086957      0.996047       0.854633
2   Test Set      0.081218      0.989848       0.850649

Best Classification Train Accuracy for classifier SVC(C=0.6, gamma=0.01) is 1.00

Best Classification Dev Accuracy for classifier SVC(C=0.5, gamma=0.001) is 1.00

Best Classification Test Accuracy for classifier SVC(C=0.5, gamma=0.001) is 0.99


Classification report for classifier SVC(C=0.5, gamma=0.001):
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        27
           1       1.00      1.00      1.00        17
           2       1.00      1.00      1.00        25
           3       1.00      1.00      1.00        22
           4       1.00      1.00      1.00        18
           5       0.95      1.00      0.97        19
           6       1.00      1.00      1.00        20
           7       0.94      1.00      0.97        16
           8       1.00      1.00      1.00        17
           9       1.00      0.88      0.93        16

    accuracy                           0.99       197
   macro avg       0.99      0.99      0.99       197
weighted avg       0.99      0.99      0.99       197


Confusion report for classifier SVC(C=0.5, gamma=0.001):
[[27  0  0  0  0  0  0  0  0  0]
 [ 0 17  0  0  0  0  0  0  0  0]
 [ 0  0 25  0  0  0  0  0  0  0]
 [ 0  0  0 22  0  0  0  0  0  0]
 [ 0  0  0  0 18  0  0  0  0  0]
 [ 0  0  0  0  0 19  0  0  0  0]
 [ 0  0  0  0  0  0 20  0  0  0]
 [ 0  0  0  0  0  0  0 16  0  0]
 [ 0  0  0  0  0  0  0  0 17  0]
 [ 0  0  0  0  0  1  0  1  0 14]]

                                                           Classifier  train_accuracy  dev_accuracy  test_accuracy
0                                            DecisionTreeClassifier()        1.000000      0.841897       0.857868
1                         DecisionTreeClassifier(min_samples_split=3)        0.984410      0.826087       0.857868
2                         DecisionTreeClassifier(min_samples_split=5)        0.967335      0.837945       0.842640
3                        DecisionTreeClassifier(min_samples_split=10)        0.941351      0.826087       0.852792
4                          DecisionTreeClassifier(min_samples_leaf=3)        0.945063      0.849802       0.862944
5     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=3)        0.945063      0.849802       0.857868
6     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=5)        0.945063      0.849802       0.862944
7    DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=10)        0.930958      0.833992       0.842640
8                          DecisionTreeClassifier(min_samples_leaf=5)        0.917595      0.814229       0.827411
9     DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=3)        0.918337      0.818182       0.822335
10    DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=5)        0.918337      0.826087       0.827411
11   DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=10)        0.918337      0.822134       0.802030
12                        DecisionTreeClassifier(min_samples_leaf=10)        0.868597      0.830040       0.812183
13   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=3)        0.868597      0.826087       0.812183
14   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=5)        0.868597      0.830040       0.807107
15  DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=10)        0.868597      0.826087       0.812183

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.868597      1.000000       0.925390
1    Dev Set      0.814229      0.849802       0.831769
2   Test Set      0.802030      0.862944       0.835025

Best Classification Train Accuracy for classifier DecisionTreeClassifier() is 1.00

Best Classification Dev Accuracy for classifier DecisionTreeClassifier(min_samples_leaf=3) is 0.85

Best Classification Test Accuracy for classifier DecisionTreeClassifier(min_samples_leaf=3) is 0.86


Classification report for classifier DecisionTreeClassifier(min_samples_leaf=3):
              precision    recall  f1-score   support

           0       0.95      0.95      0.95        20
           1       0.64      0.78      0.70        18
           2       0.81      0.76      0.79        17
           3       0.62      0.79      0.70        19
           4       0.95      0.81      0.88        26
           5       1.00      0.87      0.93        15
           6       0.90      0.79      0.84        24
           7       0.92      0.75      0.83        16
           8       0.74      0.77      0.76        22
           9       0.74      0.85      0.79        20

    accuracy                           0.81       197
   macro avg       0.83      0.81      0.82       197
weighted avg       0.83      0.81      0.82       197


Confusion report for classifier DecisionTreeClassifier(min_samples_leaf=3):
[[19  0  0  0  1  0  0  0  0  0]
 [ 0 14  0  1  0  0  0  0  1  2]
 [ 0  2 13  0  0  0  0  0  2  0]
 [ 0  0  1 15  0  0  0  1  0  2]
 [ 0  2  0  0 21  0  1  0  2  0]
 [ 0  0  0  0  0 13  1  0  0  1]
 [ 1  2  0  2  0  0 19  0  0  0]
 [ 0  1  2  0  0  0  0 12  1  0]
 [ 0  1  0  3  0  0  0  0 17  1]
 [ 0  0  0  3  0  0  0  0  0 17]]

                  Classifier  train_accuracy  dev_accuracy  test_accuracy
0     SVC(C=0.1, gamma=0.01)        0.210160      0.143911       0.123596
1     SVC(C=0.2, gamma=0.01)        0.224078      0.147601       0.123596
2     SVC(C=0.5, gamma=0.01)        1.000000      0.302583       0.258427
3     SVC(C=0.6, gamma=0.01)        1.000000      0.394834       0.314607
4       SVC(C=1, gamma=0.01)        1.000000      0.797048       0.707865
5       SVC(C=2, gamma=0.01)        1.000000      0.815498       0.764045
6       SVC(C=5, gamma=0.01)        1.000000      0.815498       0.764045
7       SVC(C=7, gamma=0.01)        1.000000      0.815498       0.764045
8      SVC(C=10, gamma=0.01)        1.000000      0.815498       0.764045
9    SVC(C=0.1, gamma=0.005)        0.388309      0.284133       0.258427
10   SVC(C=0.2, gamma=0.005)        0.846207      0.630996       0.505618
11   SVC(C=0.5, gamma=0.005)        1.000000      0.940959       0.921348
12   SVC(C=0.6, gamma=0.005)        1.000000      0.952030       0.932584
13     SVC(C=1, gamma=0.005)        1.000000      0.977860       0.966292
14     SVC(C=2, gamma=0.005)        1.000000      0.977860       0.966292
15     SVC(C=5, gamma=0.005)        1.000000      0.977860       0.966292
16     SVC(C=7, gamma=0.005)        1.000000      0.977860       0.966292
17    SVC(C=10, gamma=0.005)        1.000000      0.977860       0.966292
18   SVC(C=0.1, gamma=0.001)        0.977731      0.970480       0.966292
19   SVC(C=0.2, gamma=0.001)        0.989562      0.988930       0.966292
20   SVC(C=0.5, gamma=0.001)        0.998608      0.996310       0.966292
21   SVC(C=0.6, gamma=0.001)        0.998608      0.996310       0.966292
22     SVC(C=1, gamma=0.001)        1.000000      0.996310       0.966292
23     SVC(C=2, gamma=0.001)        1.000000      0.996310       0.977528
24     SVC(C=5, gamma=0.001)        1.000000      0.996310       0.977528
25     SVC(C=7, gamma=0.001)        1.000000      0.996310       0.977528
26    SVC(C=10, gamma=0.001)        1.000000      0.996310       0.977528
27  SVC(C=0.1, gamma=0.0005)        0.965901      0.966790       0.966292
28  SVC(C=0.2, gamma=0.0005)        0.983299      0.981550       0.966292
29  SVC(C=0.5, gamma=0.0005)        0.991649      0.992620       0.966292
30  SVC(C=0.6, gamma=0.0005)        0.993737      0.988930       0.966292
31    SVC(C=1, gamma=0.0005)        0.998608      0.992620       0.966292
32    SVC(C=2, gamma=0.0005)        1.000000      0.996310       0.966292
33    SVC(C=5, gamma=0.0005)        1.000000      0.988930       0.977528
34    SVC(C=7, gamma=0.0005)        1.000000      0.988930       0.977528
35   SVC(C=10, gamma=0.0005)        1.000000      0.988930       0.977528
36  SVC(C=0.1, gamma=0.0001)        0.909534      0.904059       0.921348
37  SVC(C=0.2, gamma=0.0001)        0.942937      0.944649       0.955056
38  SVC(C=0.5, gamma=0.0001)        0.970077      0.959410       0.966292
39  SVC(C=0.6, gamma=0.0001)        0.972860      0.963100       0.966292
40    SVC(C=1, gamma=0.0001)        0.983299      0.977860       0.966292
41    SVC(C=2, gamma=0.0001)        0.988170      0.985240       0.966292
42    SVC(C=5, gamma=0.0001)        0.995129      0.992620       0.966292
43    SVC(C=7, gamma=0.0001)        0.998608      0.996310       0.966292
44   SVC(C=10, gamma=0.0001)        0.999304      0.992620       0.966292

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.210160      1.000000       0.940586
1    Dev Set      0.143911      0.996310       0.872899
2   Test Set      0.123596      0.977528       0.847690

Best Classification Train Accuracy for classifier SVC(C=0.5, gamma=0.01) is 1.00

Best Classification Dev Accuracy for classifier SVC(C=0.5, gamma=0.001) is 1.00

Best Classification Test Accuracy for classifier SVC(C=2, gamma=0.001) is 0.98


Classification report for classifier SVC(C=2, gamma=0.001):
              precision    recall  f1-score   support

           0       1.00      1.00      1.00         6
           1       0.89      1.00      0.94         8
           2       1.00      1.00      1.00        12
           3       1.00      1.00      1.00         8
           4       1.00      1.00      1.00         8
           5       1.00      0.88      0.93         8
           6       1.00      1.00      1.00         9
           7       1.00      0.86      0.92         7
           8       1.00      0.93      0.96        14
           9       0.82      1.00      0.90         9

    accuracy                           0.97        89
   macro avg       0.97      0.97      0.97        89
weighted avg       0.97      0.97      0.97        89


Confusion report for classifier SVC(C=2, gamma=0.001):
[[ 6  0  0  0  0  0  0  0  0  0]
 [ 0  8  0  0  0  0  0  0  0  0]
 [ 0  0 12  0  0  0  0  0  0  0]
 [ 0  0  0  8  0  0  0  0  0  0]
 [ 0  0  0  0  8  0  0  0  0  0]
 [ 0  0  0  0  0  7  0  0  0  1]
 [ 0  0  0  0  0  0  9  0  0  0]
 [ 0  0  0  0  0  0  0  6  0  1]
 [ 0  1  0  0  0  0  0  0 13  0]
 [ 0  0  0  0  0  0  0  0  0  9]]

                                                           Classifier  train_accuracy  dev_accuracy  test_accuracy
0                                            DecisionTreeClassifier()        1.000000      0.863469       0.842697
1                         DecisionTreeClassifier(min_samples_split=3)        0.990257      0.856089       0.831461
2                         DecisionTreeClassifier(min_samples_split=5)        0.971468      0.859779       0.820225
3                        DecisionTreeClassifier(min_samples_split=10)        0.943633      0.859779       0.820225
4                          DecisionTreeClassifier(min_samples_leaf=3)        0.947112      0.863469       0.820225
5     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=3)        0.947112      0.867159       0.820225
6     DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=5)        0.947112      0.863469       0.808989
7    DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=10)        0.928323      0.852399       0.831461
8                          DecisionTreeClassifier(min_samples_leaf=5)        0.919972      0.845018       0.842697
9     DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=3)        0.919972      0.841328       0.842697
10    DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=5)        0.919972      0.848708       0.831461
11   DecisionTreeClassifier(min_samples_leaf=5, min_samples_split=10)        0.919972      0.848708       0.842697
12                        DecisionTreeClassifier(min_samples_leaf=10)        0.873347      0.815498       0.786517
13   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=3)        0.873347      0.811808       0.786517
14   DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=5)        0.873347      0.811808       0.786517
15  DecisionTreeClassifier(min_samples_leaf=10, min_samples_split=10)        0.873347      0.811808       0.786517

	* Min, max, mean, median of the accuracies obtained in previous step : *	

    Data Set  Min Accuracy  Max Accuracy  Mean Accuracy
0  Train Set      0.873347      1.000000       0.928018
1    Dev Set      0.811808      0.867159       0.845018
2   Test Set      0.786517      0.842697       0.818820

Best Classification Train Accuracy for classifier DecisionTreeClassifier() is 1.00

Best Classification Dev Accuracy for classifier DecisionTreeClassifier(min_samples_leaf=3, min_samples_split=3) is 0.87

Best Classification Test Accuracy for classifier DecisionTreeClassifier() is 0.84


Classification report for classifier DecisionTreeClassifier():
              precision    recall  f1-score   support

           0       0.83      1.00      0.91        10
           1       0.50      0.80      0.62         5
           2       0.75      0.86      0.80         7
           3       0.55      1.00      0.71         6
           4       1.00      0.78      0.88         9
           5       0.73      0.57      0.64        14
           6       1.00      0.90      0.95        10
           7       1.00      0.88      0.93         8
           8       1.00      0.70      0.82        10
           9       0.67      0.60      0.63        10

    accuracy                           0.79        89
   macro avg       0.80      0.81      0.79        89
weighted avg       0.82      0.79      0.79        89


Confusion report for classifier DecisionTreeClassifier():
[[10  0  0  0  0  0  0  0  0  0]
 [ 0  4  1  0  0  0  0  0  0  0]
 [ 0  1  6  0  0  0  0  0  0  0]
 [ 0  0  0  6  0  0  0  0  0  0]
 [ 0  0  0  0  7  2  0  0  0  0]
 [ 1  0  0  2  0  8  0  0  0  3]
 [ 0  1  0  0  0  0  9  0  0  0]
 [ 0  0  0  0  0  1  0  7  0  0]
 [ 1  0  1  1  0  0  0  0  7  0]
 [ 0  2  0  2  0  0  0  0  0  6]]

Accuracy Comparison of two Models
-----------------------------------
        SVC  Decision Tree
0  0.987013       0.810761
1  0.992736       0.815981
2  0.980392       0.839869
3  0.989848       0.812183
4  0.966292       0.786517
Mean 0.983 		 0.813 
Std 0.011 		 0.019 


F1 Score(Macro) Comparison of two Models
-----------------------------------------
        SVC  Decision Tree
0  0.987087       0.809509
1  0.992002       0.818125
2  0.980928       0.834213
3  0.987739       0.815741
4  0.966055       0.788117
Mean 0.983 		 0.813 
Std 0.01 		 0.017 


F1 Score(Micro) Comparison of two Models
--------------------------------------------
        SVC  Decision Tree
0  0.987013       0.810761
1  0.992736       0.815981
2  0.980392       0.839869
3  0.989848       0.812183
4  0.966292       0.786517
Mean 0.983 		 0.813 
Std 0.011 		 0.019 


F1 Score(Weighted) Comparison of two Models
----------------------------------------
        SVC  Decision Tree
0  0.987015       0.811219
1  0.992743       0.815914
2  0.980439       0.841022
3  0.989651       0.816612
4  0.966731       0.790220
Mean 0.983 		 0.815 
Std 0.01 		 0.018 


Precision Score(Macro) Comparison of two Models
-----------------------------------------------
        SVC  Decision Tree
0  0.987913       0.814631
1  0.991462       0.829403
2  0.980832       0.833100
3  0.989118       0.828451
4  0.970707       0.802273
Mean 0.984 		 0.822 
Std 0.008 		 0.013 


Precision Score(Micro) Comparison of two Models
---------------------------------------------------
        SVC  Decision Tree
0  0.987013       0.810761
1  0.992736       0.815981
2  0.980392       0.839869
3  0.989848       0.812183
4  0.966292       0.786517
Mean 0.983 		 0.813 
Std 0.011 		 0.019 


Precision Score(Weighted) Comparison of two Models
------------------------------------------------
        SVC  Decision Tree
0  0.987415       0.817796
1  0.992817       0.826412
2  0.981205       0.845787
3  0.990400       0.829884
4  0.971626       0.822523
Mean 0.985 		 0.828 
Std 0.008 		 0.011 


Recall Score(Macro) Comparison of two Models
--------------------------------------------
        SVC  Decision Tree
0  0.986658       0.811024
1  0.992622       0.817558
2  0.981747       0.839109
3  0.987500       0.812071
4  0.966071       0.808135
Mean 0.983 		 0.818 
Std 0.01 		 0.013 


Recall Score(Micro) Comparison of two Models
------------------------------------------------
        SVC  Decision Tree
0  0.987013       0.810761
1  0.992736       0.815981
2  0.980392       0.839869
3  0.989848       0.812183
4  0.966292       0.786517
Mean 0.983 		 0.813 
Std 0.011 		 0.019 


Recall Score(Weighted) Comparison of two Models
--------------------------------------------
        SVC  Decision Tree
0  0.987013       0.810761
1  0.992736       0.815981
2  0.980392       0.839869
3  0.989848       0.812183
4  0.966292       0.786517
Mean 0.983 		 0.813 
Std 0.011 		 0.019 

Process finished with exit code 0
