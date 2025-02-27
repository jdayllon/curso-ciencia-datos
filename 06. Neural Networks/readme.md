<h1 align="center">Neural Networks</h1>


# TODO
- Parameters and activations
- Random initialization and transfer learning
- SGD, Momentum, Adam, and other optimizers
- Convolutions
- Batch normalization
- Dropout y DropConnect
- Data augmentation
- Label smoothing
- Weight decay
- Entity embeddings
- Recurrent neural networks (RNNs)
- Segmentation
- Collaborative filtering (ej. movie recommendation)
- [arbitrary order (>=2) Factorization Machine](https://github.com/geffy/tffm)


### Software


<table>
  <tr>
    <th ><a href="https://www.tensorflow.org"><img src="../img/logos/TensorFlow.svg"/></a></th>
    <td></td>
  </tr>
  <tr>
    <th ><a href="https://keras.io"><img src="../img/logos/Keras.png"/></a></th>
    <td>Keras es una librería popular de redes neuronales basada en TensorFlow. Está especialmente diseñada para facilitar la creación de redes neuronales.</td>
  </tr>
  <tr>
    <th><a href="https://pytorch.org/"><img src="../img/logos/Pytorch.png"/></a></th>
    <td>Es una librería de Deep Learning diseñada por Facebook. Muchos la consideran superior a Tensorflow por su flexibilidad y facilidad. Además permite su ejecución en GPU (y varias GPUs) para acelerar los cálculos. Es la libreria más usada entre investigadores para probar sus experimentos.</td>
  </tr>
  <tr>
    <th width="200"><a href="https://www.fast.ai"><img src="../img/logos/Fastai.png"/></a></th>
    <td>Fast.ai es una librería ¡y un curso! dirigido por Jeremy Howard donde se pretende hacer el Deep Learning accesible a todo el mundo. Su librería, basada en Pytorch, tiene como máxima la simplicidad y facilitar el uso de los modelos más avanzados de redes neuronales.</td>
  </tr>
</table>





# Model


# Loss


# Train Hyperparms


# Advice for Tabular data


### Neural Network

Take the longest time to train, and require extra preprocessing such as normalisation; this normalisation needs to be used at inference time as well. They can provide great results, and extrapolate well, but only if you are careful with your hyperparameters, and are careful to avoid overfitting.

<p align="center"><img width="80%" src="img/tabular2.png" /></p>

### Conclusion

We suggest starting your analysis with a random forest. This will give you a strong baseline, and you can be confident that it's a reasonable starting point. You can then use that model for feature selection and partial dependence analysis, to get a better understanding of your data.

From that foundation, you can try Gradient Boosting and Neural Nets, and if they give you significantly better results on your validation set in a reasonable amount of time, you can use them.


### Aprende más
- [Ejemplos oficiales de Keras](https://keras.io/examples)
