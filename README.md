# MyExperimentsWithTensorflowBareMinimum
Building Deep Learning Models using Tensorflow bare minimum libraries. Without using pre-build model available in tensorflow. This leads to digging deep into model internals and understanding tensorflow from scratch.

## Motivation
Goal here is not to create high performing model, but to create various models in simplified fashion. In all experiments here, simplicity wins over accuracy. I've adopted this approach in order to understand how the high level model works under the hood.  

>***Experiment1_Simple_formula_execution_and_tensorboard_visuals:*** Basic understanding of tensorflow and tensorboard <br><br>
***Experiment2_simple_training:*** Understand training means updating weights by optimizer. Create simple trainable model (regression model) and tune/train it <br><br>
***Experiment3_DNN_noMatMul:*** Setup DNN with explicit weights & biases. Prepare model in detail (without using matmul, to understand what goes behind the hood) <br><br>
***Experiment4_DNN_simplify_using_MatMul:*** Now simplyfy DNN setup using Matmul <br><br>
***Experiment5_MNIST_usingDNN:*** MNIST digit classification using trivial DNN (still gave close to 90% accuracy, huh) <br><br>
***Experiment6_Weight_Sharing_simplistic:*** Understand how to reuse same filter for each stride in most simple & trivial setup <br><br>
***Experiment7_MNIST_createCNN:*** Building 2 layers of CNN N/W feeding into FC. Observe how kernels stride over all images.



# Instruction to Visualize tensorflow graph in tensorboard
Open CMD and follow type below:

- cd <folder_path_of_the_tensorboard_log_dir><br>
- activate <environment_name_in_which_tensorflow_installed><br>
- tensorboard --logdir .<br>
     >Notice the dot at last <br>
     Now you will get a URL link. Copy & paste it in browser. Violla, tensorboard is visible now
 
