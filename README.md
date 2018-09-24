# Catsitter 3000

I love our cat [Mochi](https://www.instagram.com/mochiputshisheadonthings/), but sometimes when we're gone for the weekend it's annoying to bribe friends to come over and literally just open a can of wet food for the little brat. Anything on the market either [has been in product development for 2 years](https://pawbot.com/), [have to buy exclusive cans and is invite only](https://www.catzenpup.com/), or require [pre-opened wet food](https://www.amazon.com/TDYNASTY-DESIGN-Automatic-Feeder-Dogs/dp/B01LRMBEN6/) which freaks me out.

Enter Catsitter 3000! You press a button on a webpage when you're away for the weekend, and it will open a can of wet food, taking pictures to verify that your favorite feline has been properly fed.
  
#### Hardware:
<ul>
  <li>Raspberry Pi 3 - $30</li>
  <li>2 x DC Motors - $26</li>
  <li>2 x Motor Brackets - $14</li>
  <li>Motor Driver - $7</li>
  <li>2 x Bar Clamps - $14</li>
  <li>Camera Module - $25</li>
  <li>Long camera ribbon - $6 (splurge!)</li>
  <li><b>Total: $122</b></li>
</ul>

<img src="https://user-images.githubusercontent.com/1938145/45935501-ff4d3c80-bf79-11e8-9226-d9b91c369984.jpg" width = "400"><br>
<img src="https://user-images.githubusercontent.com/1938145/45935474-c7de9000-bf79-11e8-9be4-c582b336e4c1.jpg" width = "600">
<img src="https://user-images.githubusercontent.com/1938145/45935400-0c1d6080-bf79-11e8-85c8-710aeb2784b1.jpg" width = "400">

#### Software:
<ul>
  <li>Mochicam powered by a simple Rails app on Heroku</li>
  <li>Raspyberry Pi uses remot3.it to keep HTTP Port open, listening for API calls</li>
  <li>Flask app on Raspberry Pi runs a script to take pictures and uploads to S3</li>
  <li>Password protected interface used for motor setup and trigger feeding</li>
</ul>

<img src="https://user-images.githubusercontent.com/1938145/45935402-0c1d6080-bf79-11e8-9f39-668aa6ed800d.png" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45935403-0c1d6080-bf79-11e8-8a03-590932cca8c6.png" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45935568-97e3bc80-bf7a-11e8-8813-cbf50fb636c8.png" width="400">

#### In Action:
[![Catfeeder V3](https://user-images.githubusercontent.com/1938145/45935958-ff9c0680-bf7e-11e8-8009-f1e243b4bfb7.png)](https://youtu.be/ParOgNfIK5U)

#### What's next?
Watch out for a V5! This needs improvement since it's a little pricey and also gets food all on his head 😅 
<br><br>
<img src="https://user-images.githubusercontent.com/1938145/45935401-0c1d6080-bf79-11e8-8209-c57514320b7e.jpg" width="300">

# Iterations

#### Version 1 - In a box
Drilled a hole in a baseball display box, this only did one pull motion and I forgot that cans need to be popped backwards first.

<img src="https://user-images.githubusercontent.com/1938145/45007267-09a79680-afcb-11e8-8b89-be13ca6164a8.jpg" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45007302-32c82700-afcb-11e8-90cf-dcb636caf0c1.jpg" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45007266-09a79680-afcb-11e8-89e1-46b1b55a07e8.jpg" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45007265-09a79680-afcb-11e8-9799-668b35808517.jpg" width="400">

#### Version 2 - Dual action
Now that I knew I needed 2 motors, I upgraded but the lid didn't even budge because of the angles. Proof of concept wood works though :+1:

<img src="https://user-images.githubusercontent.com/1938145/45007675-eaaa0400-afcc-11e8-947d-351f5ffd4a74.jpg" width="400">

#### Version 3 - More wood
Finally landed on this weird shape, the $25 camera I bought off Amazon SHOCKINGLY didn't work well, and the blue gear mostly failed

<img src="https://user-images.githubusercontent.com/1938145/45007839-9f442580-afcd-11e8-80c7-3b94a90958d9.jpg" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45007840-9fdcbc00-afcd-11e8-97af-da56c9afcdd5.jpg" width="400">

<img src="https://i0.wp.com/techpatio.com/wp-content/uploads/2018/02/instagram-logo.jpg" width="25"> &nbsp;&nbsp; [Follow Mochi putting his head on things](https://www.instagram.com/mochiputshisheadonthings/)
