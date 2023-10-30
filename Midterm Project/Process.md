<h3> 1. Narrative </h3> 
<p> The narrative was actually one of the components that kept changing. We initially wanted the narrative to be that the mirror is haunted by children and we wanted to find scary children sounds to install onto our mirror. And we kind of just left it there and focused on what and how the mirror is interactive. This worked our because all our scenarios and interactions were going to be the same and the narrative would only control the sounds and external decoration of the mirror. </p>

<h3> 2. Electronics </h3>
<p> We knew we wanted sound and light to be the moving components in our project. So we, early on, decided to that they will be responding to distance and reacting to how the person interacts/approaches the miror. We ended up with three different scenarios: </br>
1. The mirror in its normal state, not being interacted with </br>
2. The mirror when someone is close but not touching </br> 
3. The mirror when someone touches it
</p>
<h4> - Sound </h4>
<p>  We orderded the adafruit audio fx mini sound board to use since we can add long(er) sounds to it but we later found out that it was not compatable with the specific arduino we had. But because it was "smart" sound board, this meant that we can load the board with sound files and control the output with buttons connected to the pins of the sound board. For example, T00.ogg will be played when the button connected to pin 0 is being pressed. With that information, we used the arduino to mimic a button by outputting a digital high into the sound board pin and used a speaker jack to output the sound. Finding the sounds (in addition to decorating) lead us to the idea of the bloody marry narrative since the narrative/game relied heavily on sound and is played using a mirror.  </p>
<h4> - Light </h4>
<p> We ordered an LED strip since light was an important factor of our project and we wanted strong LEDs and lighting effect. We only got a part of them working and so we ended up cutting part of them and sticking them closer to the edge of the mirror so they appear brighter. </p>
<h4> - Touch </h4>
<p> We also wanted the mirror to react and scare the audience if they tried to touch it and so we used a touch sensor (FSR) to trigger a scream if it was touched</p>
<h3> 3. Decorations </h3>
<p> Since the project is halloween themed, we wanted to use fake blood to give into the "haunted look" as well as the spider webs to show age. We also wanted to invite the audience to touch the mirror so we decided to use the fake blood to write a message, prompting people to touch it.</p>

<h3> 4. Code </h3>
<p> I intially wrote down the pseudocode for the program to write down the logic of how all these components will interact with each other and what external stimuli is affecting them. I think put them into arduino and I used the labs as reference for some of the component setup. I think linked it to the external setup and had that working. However, I ran into an issue with making sure that the timing and LED patterns worked and responded to the sensors in a way without any delays ans so we implemented variables that measured "states" and that took our code from being a bunch of if statements to measuring changes in the physical state of the mirror and responding to that</p>

![](https://github.com/LiyanIbrahim/ITP-Physical-Computing/blob/main/Midterm%20Project/Screenshot%202023-10-29%20at%208.01.38%20PM.png)
![](https://github.com/LiyanIbrahim/ITP-Physical-Computing/blob/main/Midterm%20Project/Screenshot%202023-10-29%20at%208.01.47%20PM.png)
![](https://github.com/LiyanIbrahim/ITP-Physical-Computing/blob/main/Midterm%20Project/Screenshot%202023-10-29%20at%208.01.56%20PM.png)
![](https://github.com/LiyanIbrahim/ITP-Physical-Computing/blob/main/Midterm%20Project/Screenshot%202023-10-29%20at%208.02.06%20PM.png)
