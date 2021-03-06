# CS 4641 Project Proposal


## Introduction and background 

### Vehicle plate recognition system: 

Vehicle plate recognition system is used to recognize the vehicle plate number and store the information for parking charging. 
### Background: 
vehicle plate number recognition system is still limited and has low efficiency when handling cases, which includes but not limited to event parking, regular permit parking illegal parking. This incapability often will incur the congestion of the main traffic route and increase the risk of traffic incidents. In order to improve the correctness of plate recognition and thus improve the vehicle throughput, we need a better model to handle the plate recognition and save unit labor cost.


## Methodology

The most dataset we will utilize is based on image of vehicle plate. To handle the influence of variety of plates, the influence of different weather, lighting conditions and the angle between the camera and the plate objects, at the very first step, we include the 53 images of plates from 50 States in America and 350 images of plate under different lighting conditions. We might also need to include more image dataset in the future if needed to encounter emerging challenges. The dataset is obtained through roboflow.com and Kaggle.com for academic purposes. Each image in the datasets has already been preprocessed, zipped and according cropped to be identical image size and small enough for training efficiency. Since this model will not include the clustering and dimensionality reduction, we will mainly use the supervise learning to ensure the successful recognition rate. The process will be divided into two parts to guarantee the performance of the recognition model, which are training part and test part. In the training dataset, we will train the model based on the label for each plate image. The test dataset mainly serves as the evaluation of the performance for the successful recognition rate. The new feature we will include in this project will be the involvement of deep learning technology. In the past decades, the vehicle plate recognition system is mainly based on the preprocess of the captured plate images and identify each character based on the character database. However, with the help of deep learning method and enormous datasets, the process efficiency and correctness will be dramatically improved. The potential risk for this method includes failing to find a hyper parameter set to make the time cost in a reasonable range, failing to improve the overall recognition rate based on the limited training and testing datasets at hands. It also might increase the data search and fetching budget to meet this accuracy criteria. Reasonable budget will include the usage of GPU with high performance and time searching for the useful datasets. The basic estimate time for each epoch varies based on the size of each batch of dataset, the configuration of each hyper parameter. It can range from several minutes to several hours to complete this task.

## Results

The expected result of the vehicle plate recognition system will be highly efficient and capable of handling the handling a large amount of vehicle throughput in a short period of time. The expected accuracy for this model is at least an 85%. We will also include two checkpoint for this project process, which are midterm check and the final check. The midterm check will include the check for the sufficient dataset and the recognition rate. If the result is under the expectation, we need to reconfigure the process or need to optimize the model in order to achieve a better performance. The final exam will check for whether the efficiency and accuracy of recognition requirement is meet.

### Discussion
 
The success of the project will greatly reduce labor costs and reduce expenditures. The successful deployment of the model will greatly improve the vehicle throughput capacity of the parking lot per unit time and reduce the traffic congestion due to waiting in and out of the queue, thereby reducing the probability of traffic accidents near the gate.



