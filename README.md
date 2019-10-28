# Energy-Management-in-WSN
## Datasets
- [Ionosphere](https://www.kaggle.com/creepyghost/uci-ionosphere)
- [Forest CoverType](https://www.kaggle.com/uciml/forest-cover-type-dataset)

## Dependencies
 - [x] Pytorch >= 1.2
 - [x] Python >= 3.6
 - [x] Numpy 
 - [x] Pandas
 - [x] Sklearn

## Usage
 - Set path according to your directories
 - If are using cpu make sure to change "use_cuda = False"
 - Change the data file location in the code according to your requirementth according to your directories"

## Training and Testing
- For Ionosphere dataset 
```
$ python3 ionosphere.py
``` 
- For Forest Covertype Dataset
```
$ python3 covertype.py
```

## Accuracy
 - For Ionosphere data
 
 | Epoch     | Thershold | Train Accuracy  | Test Accuracy  |
 | --------- |:---------:| :--------------:| ------------:  |
 | 2000      |  0.1      |  98.95%         |  92.25%        |
 | 2000      |  0.3      |  98.57%         |  91.55%        |
 - For Forest CoverType data (Batch Size = 150)
 
 | Epoch     | Thershold | Train Accuracy  | Test Accuracy  |
 | --------- |:---------:| :--------------:| ------------:  |
 | 10000     |  0.1      |  93.58%         |  81.18%        |

## References
- [Energy Management](https://en.wikipedia.org/wiki/Energy_management)
- [Wireless Sensory Networks](https://en.wikipedia.org/wiki/Wireless_sensor_network)
- [Auto Encoder](https://web.stanford.edu/class/cs294a/sparseAutoencoder.pdf)

### Citation [[link]](https://ieeexplore.ieee.org/document/8716655)
```
B. O. Ayinde and A. Y. Barnawi, "Energy Conservation in Wireless Sensor Networks Using Partly-Informed Sparse Autoencoder," 
in IEEE Access, vol. 7, pp. 63346-63360, 2019. doi: 10.1109/ACCESS.2019.2917322 
```