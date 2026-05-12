# part-2-cnn-computer-vision

Task 6 — CNN Concept Explanation

(i) What is Convolution?

Convolution is a process where small filters scan across an image to detect important visual features such as: edges, textures ,patterns, shapes
The CNN learns these filters automatically during training.

(ii) Why is Pooling Used?

Pooling reduces image feature size while preserving important information.
Benefits: reduces computation, prevents overfitting, improves efficiency
Max pooling keeps the strongest feature values.

(iii) Why is ReLU Commonly Used?

ReLU: f(x)=max(0,x)
ReLU: introduces non-linearity, trains faster, avoids vanishing gradient problems

(iv) Why CNNs Are Better Than Feed-Forward Networks for Images

Regular neural networks: flatten images completely, lose spatial structure
CNNs: preserve spatial relationships, detect local patterns, require fewer parameters
This makes CNNs highly effective for image recognition tasks.
