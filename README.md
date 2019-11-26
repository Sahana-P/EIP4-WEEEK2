# EIP4-WEEEK2
# EIP4-WEEEK2
1.
Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 64s 1ms/step - loss: 0.2945 - acc: 0.9563 - val_loss: 0.0710 - val_acc: 0.9882
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.1029 - acc: 0.9801 - val_loss: 0.0679 - val_acc: 0.9873
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0753 - acc: 0.9818 - val_loss: 0.0471 - val_acc: 0.9918
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0605 - acc: 0.9853 - val_loss: 0.0455 - val_acc: 0.9904
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0522 - acc: 0.9867 - val_loss: 0.0405 - val_acc: 0.9900
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0467 - acc: 0.9880 - val_loss: 0.0302 - val_acc: 0.9930
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0424 - acc: 0.9889 - val_loss: 0.0294 - val_acc: 0.9930
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 64s 1ms/step - loss: 0.0374 - acc: 0.9904 - val_loss: 0.0268 - val_acc: 0.9920
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 64s 1ms/step - loss: 0.0355 - acc: 0.9909 - val_loss: 0.0308 - val_acc: 0.9923
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0334 - acc: 0.9914 - val_loss: 0.0267 - val_acc: 0.9922
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0306 - acc: 0.9918 - val_loss: 0.0249 - val_acc: 0.9936
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0286 - acc: 0.9924 - val_loss: 0.0249 - val_acc: 0.9937
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 62s 1ms/step - loss: 0.0266 - acc: 0.9933 - val_loss: 0.0228 - val_acc: 0.9941
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 62s 1ms/step - loss: 0.0259 - acc: 0.9934 - val_loss: 0.0234 - val_acc: 0.9930
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 62s 1ms/step - loss: 0.0241 - acc: 0.9940 - val_loss: 0.0234 - val_acc: 0.9945
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 62s 1ms/step - loss: 0.0237 - acc: 0.9943 - val_loss: 0.0238 - val_acc: 0.9934
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0225 - acc: 0.9944 - val_loss: 0.0234 - val_acc: 0.9935
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 62s 1ms/step - loss: 0.0215 - acc: 0.9949 - val_loss: 0.0237 - val_acc: 0.9942
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 62s 1ms/step - loss: 0.0203 - acc: 0.9951 - val_loss: 0.0252 - val_acc: 0.9930
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 63s 1ms/step - loss: 0.0188 - acc: 0.9957 - val_loss: 0.0251 - val_acc: 0.9925
<keras.callbacks.History at 0x7f7172271390>


2 .Print score = [0.01988825887264684, 0.9941]


3.
Less number of convolution gives less number of parameters.So, after initial convolution added maxpooling.
I have used total of 5 convolutions and have got 15.2k parameters..
Total params: 15,266
Trainable params: 15,118
Non-trainable params: 148
Since it is a 28*28 input image the kernel size can be less.So used kernel size of 16.
last convolution size will be 7*7 and I have used kernal size also 7*7,which will give only one number.
Used dropout of 0.1
The highest accuracy is got at 15th epoch which is 99.45
