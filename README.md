# Digit-Recognition-using-MNIST

UNDERSTANDING THE IDX FORMAT:

The MNIST dataset is provided in the format of IDX. This format is handy when operating with vectors and high dimensional matrices of different numerical types. Starting with the magic number in the description column available in the file format. We can define a magic number as an integral value (say MSB first), where the first 2 bytes are always seen to be zero. This gives us the following information:
1. The 0000 (2 bytes) informing the beginning of the file.
2. 08 tells us that third byte is of unsigned byte type.
3. The fourth byte, 03 tells us that the matrix has three dimensions and 01 informing with just one dimension.

I have used the in-built TensorFlow's input_data.read_data_sets function to access and read the IDX files.

NEURAL NETWORKS or DEEP LEARNING:

Neural Networks mimics the working of how our brain works. The network is connected with multilayers composited from nodes. A node is just a perception which takes an input, performs some computation and passes it through a node’s activation function. This is to show up to what context signal progress proceeds through the network to perform classification.

ALGORITHM
1. Initializing the weights randomly (not by keeping them zero)
2. Implementing forward propagation to achieve hθ​(x(i)).
3. Compute cost
4. Use gradient descent or any built-in optimization function to minimize the cost function with weights of theta Θ.
