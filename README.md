# Hello, TDF Instructors and TAs!
Welcome to my GitHub repository! - Isabella Wang :) <br>

<div width="100%" align="left">
<img width="33%" height="220" src="assets/yay.gif">   
<img width="33%" height="220" alt="Pill Box" src="assets/mario.gif">   
<img width="33%" height="220" alt="Pill Box" src="assets/cattyping.gif">   
</div>

# Outline
⭐️ [Week 1](README.md#%EF%B8%8F-week-1---report-1)

⭐️ [Week 2](README.md#%EF%B8%8F-week-2---report-2)



<br>
<br>
<br>

# 🗓️ Week 1 - Report 1 #
## Week of 09/02/2024


### Introduction

This week i laser cut 2 pill boxes out of plywood.

The idea was for me and my roomate to have a matching set. The flower shape gives a friendly and girly appearance.
The flower top spins around and snaps onto the open sections, leaving access to retrieve the contents.

We thought about 3d printing it, but decided aginst it because of the texture and cheap feel. The plywood gives a heavier sensation and a nicer finish. 


<img width="50%" alt="Both Pillboxes" src="assets/both-pillboxes.png">   


### Process

1. Ai the layers
2. Cut the layers out of 3/4 plywood
3. Stack the layers with wood glue and clean up the edges
4. Sand the edges and surfaces


### Hiccups
1. We ran out of magnets and havent been able to test the mechanism.
2. I tried to sand off the burnt edges of the laser cut, but was dissapointed with the result. It looks patchy and oddly naked.

<div align="left">
<img height="200" width="200" alt="Sanded Sides" src="assets/sanded-pillbox.png">   
<img height="200" width="200" alt="Pill Box" src="assets/unsanded-pillbox.png">   
</div>

### Next steps

1. Purchase magnets and place them
2. Paint sides
3. Assemble the pill box
4. Put vitamins inside


<br>
<br>

# 🗓️ Week 2 - Report 2 #
## Week of 09/09/2024


📌 [Monday - Grasshopper Experimentation](README.md#monday---grasshopper-experimentation)

📌 [Thursday - Class Exploration](README.md#thursday---class-exploratioon) 

📌 [Weekly Update - Computational Design Research](README.md#weekly-update---computational-design-research) 

<br>

## Monday - Grasshopper Experimentation

### Diagrams

<div align="left">
<img height="200" alt="Diagram 1 - Phone Stand" src="assets/diagram1.png">   
<img height="200" alt="Diagram 2 - Phone" src="assets/diagram2.png">   
</div>
<img height="400" alt="Diagram 3 - Phone Stand minus Phone" src="assets/diagram3.png">   

The diagrams were made by readign each of the nodes and identifying how they feed into each other. It was especially helpfull to understand that almost all parameters are customizable.
The designer has to create a system in which those nodes interact. Grasshopper allows to only define the overall arcitecture has to be defined. All minutia can be altered at any point. 

E.G.
In the current design, the smaller spehere remains substracted from the bigger sphere. But the designer is still able to change any size and alignment.
While the phone would be a headache to remove, the size, thickness and alignemnemt to the table can be easily altered.

<br>

### Baked forms

**First test:**
- Wanted a portrait mode phone
- This lead to thicker walls for balance. The ball on the backside grew until about half the phone height.
- The limits on threshhold caused the substracted cylinder to be shifted upwards.
- The phone distance from the table was shortened

<div align="left">
<img height="200" alt="Test 1 - Perspective View" src="assets/exp1.png">   
<img height="200" alt="Test 1 - Top View" src="assets/exp2.png">   
<img height="200" alt="Test 1 - Right ViewPerspective" src="assets/exp3.png">   
</div>

<br>

**Second test:**
- Wanted to do the lowest lanscape mode i could
- I changed the Z on both of the speheres and the cylinder
- It was a balance between getting lower but not triggering the threshold warnings
- the phone was the lowest it could go without risking the area below being too thin to crack

<div align="left">
<img height="200" alt="Test 2 - Right View" src="assets/exp21.png">   
<img height="200" alt="Test 2 - Perspective View" src="assets/exp22.png">   
<img height="200" alt="Test 2 - Top View" src="assets/exp23.png">   
</div>

<br>

**Third test:**
- Wanted a round back section of the stand
- I shifted both spheres as low as they would go
- This is the design im most content with.
- Thye round look gives it an adorable and approachable style im drawn to

<div align="left">
<img height="200" alt="Test 3 - Perspective View" src="assets/exp31.png">   
<img height="200" alt="Test 3 - Right View" src="assets/exp32.png">   
<img height="200" alt="Test 3 - Top View" src="assets/exp33.png">   
</div>

<br>

## Thursday - Class Exploratioon

Following along to the class tutorial. I was a bit lost doing Grasshopper from the start. It was easy to decode what the pre-made file was doing. It was mostly reading through the nodes and seeing how they connected. Making it, required knowing where to find the relevant buttons and requests, which i kept losing in the screen. I ended up getting help from my table mates, who guided me through it

The shape was simple, just a squaew with a cylinder substracted from it. But it made me realize how usefull the modularity of Grasshopper is. In any other program like Fusion or Blender, the shapes are pretty set in stone; having parameters that are easy to edit sppeds the testing process along. 

<img width="500" alt="Class Diagram" src="assets/classdiagram.png">   

<div align="left">
<img height="200" alt="Class Test - Top View" src="assets/class1.png">   
<img height="200" alt="Class Test - Right View" src="assets/class2.png">   
<img height="200" alt="Class Test - Front View" src="assets/class3.png">   
</div>


<br>

## Weekly Update - Computational Design Research

### Inspiration Board
I took inspiration from Retro product design, specifically lamp designs. Im attracted to the round and homely feel. 
The transparecy and sleekness to the acrylic give it a visually appealing look. 
After looking through alternatives, I decided for a magnetic stand. It supports the most devices and it's easiest to interact with

<img width="500" alt="Moodboard" src="assets/moodboard.png">   

### Possible Diagram
- The design will have a round base
- Going up to a column.
- On the top there will be a ball bearing holding up the magnet. The ball bearing allows for ease of changing the phones angle and orientation. 

### Next steps
1. Making the sketch of the stand in paper
2. Making model in Grashopper

<br>
<br>

# 🗓️ Week 2 - Report 2 #
## Week of 09/09/2024


📌 [VIDEO LINK](https://youtu.be/56ulLLgMZa8)

<br>

## Computational Design - Process and Final

### Rhino + Grasshoper
1. I began by determining the shape of the base. I tried to make it by substracting a donut shape from a cylinder in order to have a sloped angle from the body to the lower section. But i was dissatiesfied with the result. I ended up making a low cylinder with a cone on top
2. For the body i made a circle adn extruded it into a cylinder
3. For the top section fo the body I made 2 points to determine the start and end of an arc
4. I made a circle and extruded it starting from the top section of the body cylinder. Then used the "bend" node to bend the cylinder along the arc
5. I capped all the forms and did solid union to join them together


### Physical Process
1. I laser cut all the pieces from acrylic in the recycling bin
2. I peeled all the acrylic bits
3. I tried to attach the pieces with a heating gun, and it did work very well because it left no marks. But the pieces unstuck from themselves
4. So I switched to acrylic weld, attaching all the pieces together
5. After I attahced them, the transparent material displayed bubbles and imperfections from the weld
6. I tried to polish it, re-attaching pieces and softly dremeling. I ended up deciding for sandining the surface
7. I sanded the full surface to make it foggy. The finish was smoother to the touch and fit perfect with its purpose
8. I attached the ball bearing and magnet i purchased from amazon (it cost 8 bucks for 2 mounts)
9. It was working when the phone was only in portrait mode. I wanted to be able to rotate it in all angles so I had to attach a final bigger ring to offset the weight. 

### Reflections
1. I enjoyed the matieral way more than 3D printing it. I thought 3D printing it would make it too light and flimsy, the acrylic gave it the weight it needs to feel like a product adn not a draft
2. The foggy final texture was my favorite happy accident. It's so satifying to interact with. Even people who have laser cut acrylic before are a bit perplexed by the finish
3. Im glad i spent my time in the design of the body instead of dealing with the minutia of making a ball bearing. Purchasing that part allowed me to thing of the whole as a system and not wase time in details
4. Im very pleased with the final design
5. Im very surprised i was able to navigate Grasshopper and Rhino with ease towards the end. I was very baised towards working with Blender or Fusion as I have experience in them, but as I worked more with Grasshopper I understood why its the best tool to use for designs you are not entirely sure about. It's best for drafting and deciding than any other program

### What I would do different
1. I would sand the independent pieces before attachign them. Since I didnt know that was the texture I wanted, I sanded it after attaching.
2. I would make a jig to make sure all the pieces are attached in the correct place. In this version I used rulers and additional pieces but it still had bumps and misaligned pieces. 

### Video
📌 [VIDEO LINK](https://youtu.be/56ulLLgMZa8)

<br>
<br>
---
## Quick Links ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
