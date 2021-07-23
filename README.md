# Keras_LSTM_Diagram

Understanding Keras Recurrent Nets' structure and data flow (mainly LSTM) in a single diagram.

Actually as I was working on understanding how `Recurrent Neural Networks` really work and what gives these special network architectures this high power and efficiency, especially when working with sequence datasets, I found many difficulties to get the whole concept clearly into my mind. I was very familiar with `Convolutional Neural Networks` and fully-connected `Feed-Forward` architectures, where I had been working with these networks for a long time ago, and I can simply describe it as an easy-to-cut cake. However, when talking about  `Recurrent Nets` _(e.g. LSTM's, GRU's …)_ things gets much more complex.

So, when it came into building up my own `LSTM` model for the first time, I decided to use **Keras framework** _(because I was very familiar with)_, and I realized then that the worst and the hardest part was about understanding how to prepare and transform my input data to match the Keras model input expectations, and how to transform my training and validation labels to match the output of the network for validation and testing. Besides, when working with LSTM's you will find that there are a lot of network-special parameters that you must understand and take care of in order to start the game.

Finally after having a clear and sharp view of this problem, and because all of what I passed through, _I decided to summarize the main flow of Keras LSTM networks in the [this diagram][2] for the public benefit_.

Please note that the following diagram describes Keras LSTM layers, however the same diagram, as it is, is applicable for GRU's, with a minor difference between both structures in the inner shape of the processing units _(nodes)_.

For Keras LSTM code example, I think that [Mr.Jason Brownlee has a great blog here that worth to check][3].

# Diagram
Please try to read the diagram from bottom to top for better flow coherence.

<img src="https://github.com/MohammadFneish7/Keras_LSTM_Diagram/blob/master/LSTM_keras_model.bmp">

# License
This project is licensed under [GNU General Public License][1].
 
# Donate
Please consider to donate if you found this helpful. 

- *ETH*: 0x8c64753c1678D1823Fc73B8990052Ed9a106f641
- *BTC*: 1JE2811s3NWwDEvL8EbB4U1QB8GoPgJKDL


[1]: https://github.com/MohammadFneish7/Keras_LSTM_Diagram/blob/master/LICENSE
[2]: https://github.com/MohammadFneish7/Keras_LSTM_Diagram/blob/master/LSTM_keras_model.bmp
[3]: https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/
 
 
