### 'Punched cards' for Fashion-MNIST

*Object recognition by sparse random binary data lookup. Based on [this article](https://petr-kovalev.medium.com/punched-cards-object-recognition-97523a98857b)*

Performing single-shot Fashion-MNIST objects recognition by lookup over the most representative sparse input bit sets of the training data (out of 28⋅28⋅8 = 6272 bits per training sample)


Bit vector set similarity evaluation using the maximum spanning tree is described in [this article](https://petr-kovalev.medium.com/bit-vector-set-similarity-maximum-spanning-tree-2121b05c7b29)

The same algorithm applied to the QMNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-qmnist)

The same algorithm applied to the Oracle-MNIST dataset [is here](https://github.com/Petr-Kovalev/punched-cards-oracle-mnist)

### Program output:
```
Punched card bit length: 8

Average single-shot correct recognitions on fine-tune iteration: 13816, 13525

Top punched card per input:
Training results: 26439 correct recognitions of 60000
Test results: 4318 correct recognitions of 10000

Top 39 (5%) punched cards per input:
Training results: 37506 correct recognitions of 60000
Test results: 6161 correct recognitions of 10000

All punched cards:
Training results: 42378 correct recognitions of 60000
Test results: 6965 correct recognitions of 10000

Punched card bit length: 16

Average single-shot correct recognitions on fine-tune iteration: 17690, 17925, 18054, 18110, 18125, 18124

Top punched card per input:
Training results: 27040 correct recognitions of 60000
Test results: 4466 correct recognitions of 10000

Top 19 (5%) punched cards per input:
Training results: 38868 correct recognitions of 60000
Test results: 6367 correct recognitions of 10000

All punched cards:
Training results: 43809 correct recognitions of 60000
Test results: 7195 correct recognitions of 10000

Punched card bit length: 32

Average single-shot correct recognitions on fine-tune iteration: 22180, 22714, 23060, 23266, 23385, 23461, 23500, 23515, 23519, 23514

Top punched card per input:
Training results: 28434 correct recognitions of 60000
Test results: 4665 correct recognitions of 10000

Top 9 (5%) punched cards per input:
Training results: 40266 correct recognitions of 60000
Test results: 6628 correct recognitions of 10000

All punched cards:
Training results: 44518 correct recognitions of 60000
Test results: 7279 correct recognitions of 10000

Punched card bit length: 64

Average single-shot correct recognitions on fine-tune iteration: 27204, 27628, 27911, 28100, 28242, 28339, 28406, 28450, 28483, 28501, 28508, 28507

Top punched card per input:
Training results: 31868 correct recognitions of 60000
Test results: 5135 correct recognitions of 10000

Top 4 (5%) punched cards per input:
Training results: 39346 correct recognitions of 60000
Test results: 6427 correct recognitions of 10000

All punched cards:
Training results: 44765 correct recognitions of 60000
Test results: 7312 correct recognitions of 10000

Punched card bit length: 128

Average single-shot correct recognitions on fine-tune iteration: 31871, 32308, 32555, 32691, 32785, 32845, 32887, 32921, 32942, 32955, 32964, 32974, 32976, 32970

Top punched card per input:
Training results: 35077 correct recognitions of 60000
Test results: 5714 correct recognitions of 10000

Top 2 (5%) punched cards per input:
Training results: 39231 correct recognitions of 60000
Test results: 6445 correct recognitions of 10000

All punched cards:
Training results: 44752 correct recognitions of 60000
Test results: 7308 correct recognitions of 10000

Punched card bit length: 256

Average single-shot correct recognitions on fine-tune iteration: 35171, 35528, 35875, 36067, 36199, 36276, 36330, 36375, 36407, 36425, 36437, 36441, 36454, 36460, 36465, 36468, 36464

Top punched card per input:
Training results: 39199 correct recognitions of 60000
Test results: 6429 correct recognitions of 10000

Top 1 (5%) punched cards per input:
Training results: 39199 correct recognitions of 60000
Test results: 6429 correct recognitions of 10000

All punched cards:
Training results: 44519 correct recognitions of 60000
Test results: 7247 correct recognitions of 10000

Press "Enter" to exit the program...
```
