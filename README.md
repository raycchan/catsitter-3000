# Catsitter 3000

I love our cat [Mochi](https://www.instagram.com/mochiputshisheadonthings/), but sometimes when we're gone for the weekend it's annoying to bribe friends to come over and literally just open a can of wet food for the little brat. Anything on the market either [has been in product development for 2 years](https://pawbot.com/), [have to buy exclusive cans and is invite only](https://www.catzenpup.com/), or require [pre-opened wet food](https://www.amazon.com/TDYNASTY-DESIGN-Automatic-Feeder-Dogs/dp/B01LRMBEN6/) which freaks me out.

Enter Catsitter 3000! 

TBD images:
<Final image>
<Final image back>
<Final video>
<Mochi Cam>
<Mochi Cam admin page>
  
Hardware:
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

Software:
<ul>
  <li>Mochicam powered by a simple Rails app on Heroku</li>
  <li>Raspyberry Pi uses remot3.it to keep HTTP Port open, listening for API calls</li>
  <li>Flask app on Raspberry Pi runs a script to take pictures and uploads to S3</li>
  <li>Password protected interface used for motor setup and trigger feeding</li>
</ul>

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

# Learnings

<ul>
  <li>Hardware is 27 times harder than software, anything and everything will go wrong. You'll spend 3 hours debugging a loose wire but is extremely rewarding when you get it</li>
  <li>Sketch out exactly how everything will work. You will fail many many times but each time is an opportunity to take what's working and iterate (I know, :corn:)</li>
  <li>Spend the extra few bucks and get a better part, $5 discount for a knockoff version from China isn't worth it</li>
  <li>Cats get really annoyed when you tease them with half opened cans during testing</li>
</ul>

<img src="https://i0.wp.com/techpatio.com/wp-content/uploads/2018/02/instagram-logo.jpg" width="25"> &nbsp;&nbsp; [Follow Mochi putting his head on things](https://www.instagram.com/mochiputshisheadonthings/)
