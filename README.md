# A-Simple-ResNet-Model
Showcasing a simple ResNet50 for Dog Breed Classification

Optionally loads weights can be pre-trained on ImageNet as below

tf.keras.applications.ResNet50(
    include_top=True, weights='imagenet', input_tensor=None, input_shape=None,
    pooling=None, classes=1000, **kwargs
)
