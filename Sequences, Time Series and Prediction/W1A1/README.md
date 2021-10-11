## Screenshots from the lectures<br>

![1](screenshots/1.PNG)<br><br>
![2](screenshots/2.PNG)<br><br>
![3](screenshots/3.PNG)<br><br>
![4](screenshots/4.PNG)<br><br>
![5](screenshots/5.PNG)<br><br>
![6](screenshots/6.PNG)<br><br>
![7](screenshots/7.PNG)<br><br>
![8](screenshots/8.PNG)<br><br>
![9](screenshots/9.PNG)<br><br>
![10](screenshots/10.PNG)<br><br>
![11](screenshots/11.PNG)<br><br>
![12](screenshots/12.PNG)<br><br>
![13](screenshots/13.PNG)<br><br>
**You generally don't want one year and a half, or else some months will be represented more than others. While this might appear a little different from the training validation test, that you might be familiar with from non-time series data sets. Where you just picked random values out of the corpus to make all three, you should see that the impact is effectively the same. Next you'll train your model on the training period, and you'll evaluate it on the validation period. Here's where you can experiment to find the right architecture for training. And work on it and your hyper parameters, until you get the desired performance, measured using the validation set. Often, once you've done that, you can retrain using both the training and validation data. And then test on the test period to see if your model will perform just as well. And if it does, then you could take the unusual step of retraining again, using also the test data. But why would you do that? Well, it's because the test data is the closest data you have to the current point in time. And as such it's often the strongest signal in determining future values. If your model is not trained using that data, too, then it may not be optimal. Due to this, it's actually quite common to forgo a test set all together. And just train, using a training period and a validation period, and the test set is in the future.**<br><br>
![14](screenshots/14.PNG)<br><br>
**Fixed partitioning like this is very simple and very intuitive, but there's also another way. We start with a short training period, and we gradually increase it, say by one day at a time, or by one week at a time. At each iteration, we train the model on a training period. And we use it to forecast the following day, or the following week, in the validation period. And this is called roll-forward partitioning. You could see it as doing fixed partitioning a number of times, and then continually refining the model as such. For the purposes of learning time series prediction in this course, will learn the overall code for doing series prediction.**<br><br>
![15](screenshots/15.PNG)<br><br>
![16](screenshots/16.PNG)<br><br>
![17](screenshots/17.PNG)<br><br>
![18](screenshots/18.PNG)<br><br>
![19](screenshots/19.PNG)<br><br>
![20](screenshots/20.PNG)<br><br>


## Quiz <br>

![q1](screenshots/q1.PNG)<br><br>
![q2](screenshots/q2.PNG)<br><br>
![q3](screenshots/q3.PNG)<br><br>
![q4](screenshots/q4.PNG)<br><br>
![q5](screenshots/q5.PNG)<br><br>
![q6](screenshots/q6.PNG)<br><br>
![q7](screenshots/q7.PNG)<br><br>
![q8](screenshots/q8.PNG)<br><br>
![q9](screenshots/q9.PNG)<br><br>
