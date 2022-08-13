### 'Punched cards' for Fashion-MNIST

*Object recognition by sparse random binary data lookup. Based on [this article](https://petr-kovalev.medium.com/punched-cards-object-recognition-97523a98857b)*

Performing single-shot Fashion-MNIST objects recognition by lookup over the most representative sparse input bit sets of the training data (out of 28⋅28⋅8 = 6272 bits per training sample)


Bit vector set similarity evaluation using the maximum spanning tree is described in [this article](https://petr-kovalev.medium.com/bit-vector-set-similarity-maximum-spanning-tree-2121b05c7b29)

The same algorithm applied to the QMNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-qmnist)

The same algorithm applied to the Oracle-MNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-oracle-mnist)

### Program output:
```
Punched card bit length: 8

Top punched card per input:
Training results: 26800 correct recognitions of 60000
Test results: 4342 correct recognitions of 10000

Top 39 (5%) punched cards per input:
Training results: 36072 correct recognitions of 60000
Test results: 5953 correct recognitions of 10000

All punched cards:
Training results: 41446 correct recognitions of 60000
Test results: 6829 correct recognitions of 10000

Punched card bit length: 16

Top punched card per input:
Training results: 29073 correct recognitions of 60000
Test results: 4735 correct recognitions of 10000

Top 19 (5%) punched cards per input:
Training results: 37789 correct recognitions of 60000
Test results: 6253 correct recognitions of 10000

All punched cards:
Training results: 41675 correct recognitions of 60000
Test results: 6843 correct recognitions of 10000

Punched card bit length: 32

Top punched card per input:
Training results: 29277 correct recognitions of 60000
Test results: 4767 correct recognitions of 10000

Top 9 (5%) punched cards per input:
Training results: 38323 correct recognitions of 60000
Test results: 6309 correct recognitions of 10000

All punched cards:
Training results: 41726 correct recognitions of 60000
Test results: 6821 correct recognitions of 10000

Punched card bit length: 64

Top punched card per input:
Training results: 32488 correct recognitions of 60000
Test results: 5273 correct recognitions of 10000

Top 4 (5%) punched cards per input:
Training results: 38195 correct recognitions of 60000
Test results: 6288 correct recognitions of 10000

All punched cards:
Training results: 41606 correct recognitions of 60000
Test results: 6805 correct recognitions of 10000

Punched card bit length: 128

Top punched card per input:
Training results: 34998 correct recognitions of 60000
Test results: 5693 correct recognitions of 10000

Top 2 (5%) punched cards per input:
Training results: 37535 correct recognitions of 60000
Test results: 6159 correct recognitions of 10000

All punched cards:
Training results: 41521 correct recognitions of 60000
Test results: 6777 correct recognitions of 10000

Punched card bit length: 256

Top punched card per input:
Training results: 36992 correct recognitions of 60000
Test results: 6046 correct recognitions of 10000

Top 1 (5%) punched cards per input:
Training results: 36992 correct recognitions of 60000
Test results: 6046 correct recognitions of 10000

All punched cards:
Training results: 41172 correct recognitions of 60000
Test results: 6717 correct recognitions of 10000

Press "Enter" to exit the program...
```
