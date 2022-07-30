# Catsitter 3000

I love our cat [Mochi](https://www.instagram.com/mochiputshisheadonthings/), but sometimes when we're gone for the weekend it's annoying to bribe friends to come over and literally just open a can of wet food for the little brat. Anything on the market either [has been in product development for 2 years](https://pawbot.com/), [have to buy exclusive cans and is invite only](https://www.catzenpup.com/), or requires [pre-opened wet food](https://www.amazon.com/TDYNASTY-DESIGN-Automatic-Feeder-Dogs/dp/B01LRMBEN6/) which freaks me out.

Enter Catsitter 3000! You press a button remotely to dispense a tasty can of wet food for your favorite feline.

### Version 7 (current)


# Iterations

### Version 6

Wanted to create a version that would not need wifi and photo uploading features. Since I had cameras around the house, and I just needed a timer instead of an on-demand button.

<img src="https://user-images.githubusercontent.com/1938145/181936198-55e560eb-5b95-4a04-a2fe-a0879050a309.jpg" width="400">
<img src="https://user-images.githubusercontent.com/1938145/181936196-b6fad2f3-ef07-4390-adb8-063886106e54.jpg" width="400">

#### Hardware:
<ul>
  <li>Can Opener - $25</li>
  <li>Raspberry Pi Zero W - $30</li>
  <li>Raspberry Pi Case - $5</li>
  <li>240x240 Display - $15</li>
  <li>High Torque Servo - $6</li>
  <li>Servo Arm - $3</li>
  <li>Servo - $3</li>
  <li>Mini breadboard - $1</li>  
  <li>Micro USB splitter cable - $3</li>  
  <li>Micro USB breakout board - $2</li>  
  <li>Power cable - $10</li>  
  <li><b>Total: $</b></li>
</ul>

### Version 5

This was the overengineered version, complete with a hosted webpage allowing you to open a can of wet food on-demand, as well as snapping pictures during feeding.
  
#### Hardware:
<ul>
  <li>Can Opener - $20</li>
  <li>Raspberry Pi 3 - $30</li>
  <li>DC Motor - $13</li>
  <li>Motor Bracket - $7</li>
  <li>Motor Driver - $7</li>
  <li>Servo - $3</li>
  <li>Camera Module - $25</li>
  <li>Hot Glue Gun - $0 (Already had)</li>
  <li><b>Total: $105</b></li>
</ul>

<img src="https://user-images.githubusercontent.com/1938145/51092460-97f40c00-1765-11e9-9da0-187ae7bf109e.jpg" width="400">

<a href="https://youtu.be/W7FxJTYr2lE">
  <img src="https://user-images.githubusercontent.com/1938145/51092287-83af0f80-1763-11e9-9bfe-01d34b14c131.png" width="600"> </a>
  
#### Software:
<ul>
  <li>Mochicam powered by a simple Rails app on Heroku</li>
  <li>Raspyberry Pi uses remot3.it to keep HTTP Port open, listening for API calls</li>
  <li>Flask app on Raspberry Pi runs a script to take pictures and uploads to S3</li>
  <li>Password protected interface used to check status and trigger feeding</li>
</ul>

<img src="https://user-images.githubusercontent.com/1938145/51092136-0a62ed00-1762-11e9-89c0-b69915b3e5b1.png" width="400">
<img src="https://user-images.githubusercontent.com/1938145/51092137-0a62ed00-1762-11e9-9255-455d11564dd0.png" width="400">
<img src="https://user-images.githubusercontent.com/1938145/51092513-2072ac80-1766-11e9-9dfb-040f930f2dd2.png" width="400">

### Version 4
First working version! But only did 40% of the time. 
Total Cost: $122

<img src="https://user-images.githubusercontent.com/1938145/45935501-ff4d3c80-bf79-11e8-9226-d9b91c369984.jpg" width = "400"><br>
<img src="https://user-images.githubusercontent.com/1938145/45935474-c7de9000-bf79-11e8-9be4-c582b336e4c1.jpg" width = "600">
<img src="https://user-images.githubusercontent.com/1938145/45935400-0c1d6080-bf79-11e8-85c8-710aeb2784b1.jpg" width = "400">

### Version 3
Improved on motor placement and added a camera, but it was $25 off of Amazon and SHOCKINGLY didn't work well.

<img src="https://user-images.githubusercontent.com/1938145/45007840-9fdcbc00-afcd-11e8-97af-da56c9afcdd5.jpg" width="400">

### Version 2
First proof of concept with 2 motors and just gluing wood.

<img src="https://user-images.githubusercontent.com/1938145/45007675-eaaa0400-afcc-11e8-947d-351f5ffd4a74.jpg" width="400">

### Version 1
Drilled a hole in a baseball display box, forgot that pull-tabs required a two-fold action.

<img src="https://user-images.githubusercontent.com/1938145/45007302-32c82700-afcb-11e8-90cf-dcb636caf0c1.jpg" width="400">
<img src="https://user-images.githubusercontent.com/1938145/45007265-09a79680-afcb-11e8-9799-668b35808517.jpg" width="400">

<img src="https://i0.wp.com/techpatio.com/wp-content/uploads/2018/02/instagram-logo.jpg" width="25"> &nbsp;&nbsp; [Follow Mochi putting his head on things](https://www.instagram.com/mochiputshisheadonthings/)
