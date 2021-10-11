## Screenshots from the lectures<br>

![1](screenshots/1.PNG)<br><br>
![2](screenshots/2.PNG)<br><br>
![3](screenshots/3.PNG)<br><br>
![4](screenshots/4.PNG)<br><br>
![5](screenshots/5.PNG)<br><br>
![6](screenshots/6.PNG)<br><br>
![7](screenshots/7.PNG)<br><br>
![8](screenshots/8.PNG)<br><br>
**Once it's flattened, it's easy to shuffle it. You call a shuffle and you pass it the shuffle buffer. Using a shuffle buffer speeds things up a bit. So for example, if you have 100,000 items in your dataset, but you set the buffer to a thousand. It will just fill the buffer with the first thousand elements, pick one of them at random. And then it will replace that with the 1,000 and first element before randomly picking again, and so on. This way with super large datasets, the random element choosing can choose from a smaller number which effectively speeds things up.**<br><br>
![9](screenshots/9.PNG)<br><br>
![10](screenshots/10.PNG)<br><br>
![11](screenshots/11.PNG)<br><br>
**After training with this, we can then plot the last per epoch against the learning rate per epoch by using this code, and we'll see a chart like this. The y-axis shows us the loss for that epoch and the x-axis shows us the learning rate. We can then try to pick the lowest point of the curve where it's still relatively stable like this, and that's right around 7 times 10 to the -6. So let's set that to be our learning rate and then we'll retrain. So here's the same neural network code, and we've updated the learning rate, so we'll also train it for a bit longer. Let's check the results after training for 500 epochs. Here's the codes to plot out the loss that was calculated during the training, and it will give us a chart like this.**<br><br>
![12](screenshots/12.PNG)<br><br>
![13](screenshots/13.PNG)<br><br>
![14](screenshots/14.PNG)<br><br>


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
![q10](screenshots/q10.PNG)<br><br>