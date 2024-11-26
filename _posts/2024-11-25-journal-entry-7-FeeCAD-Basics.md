# FreeCAD Basics

**OVERVIEW**

For this journal entry we are working with a software called FreeCad. As soon as I saw the app for the first time, I instantly realized two things:

1. FreeCAD is much more complex than Tinkercad
2. FreeCAD seems much more interesting than Tinkercad, and I will enjoy working with it more

After completing this assignment, I can definitely say that only one of those things happened to be true. (it's not the second one)

**OBJECT 1 - basic part tutorial**

For the first object, we just had to complete the tutorial from the internet. The tutorial was quite good - even though there were some button and feature names that were different from the actual names in the app, the tutorial was super detailed and if you follow each step carefully, there's little to no chance for you to mess it up. This object took me about 20 minutes to finish, and overall was nice and smooth to build. Pretty much the only problem I faced in the process was at the very last step, when I was trying to change the refine property for the pocket to hide the intersection lines of the blocks. For some reason, it didn't work. Probably I was trying to change the refine property on a wrong feature, but anyways, here is my first object:

![image](https://github.com/user-attachments/assets/df93abea-b9b7-49db-9527-4076b4e60ff0)
![image](https://github.com/user-attachments/assets/2a97f4fa-70b2-4524-ba87-e63fec1bb0ed)

**OBJECT 2 - desk cord clip**

The second object we need to create for this assignment is a clip that attaches to the desk edge and holds the charging cable for laptop or anything else. This object is a bit more complicated than the first one simply because there is no tutorial to follow - I need to design, measure, and create the object by myself. According to the requirements, we can't glue or screw the object into the table - it has to hold itself on the edge of the desk with nothing but physics. Before I start this object, I need to measure the diameter of my charging cable and the desk:

![image](https://github.com/user-attachments/assets/2649d53b-c49d-4ad0-9ebc-b9027aca60bc)
![image](https://github.com/user-attachments/assets/047d48dc-14b4-442d-bcec-0355353c5477)

Therefore, my dimensions are:
Desk "thickness" = 48 mm
Cord diameter in a thin spot = 4 mm
Cord diameter in a wide spot = 11 mm

After taking all the measurements, I had to actually come up with the design of the cord holder that I would create. Since I presumably have some serious issues with imagination and creativity (or at least I think so), I started googling for design ideas right away, and found one that I liked and decided to create something like it:

![image](https://github.com/user-attachments/assets/5d583542-62cc-479d-b1be-7ae2439c955c)
^Source [link](https://www.printables.com/model/913282-desk-edge-cable-organizermulti-cable-clip)

First, I started with creating the clip that would be attached to the table, which was pretty easy to make - a sketch with the right dimensions, constraining everything and the center of the axis, then padding it making the length equal to 55 mm. (Why 55? - Because I wanted to make my cord clip thing to hold up to 3 cables, and by using simple calculations, when making one thread for cord 5 mm long, and keeping 1 cm between them, we get 55 mm).

![image](https://github.com/user-attachments/assets/0051b514-3807-45c2-bd68-013e340d5d00)
![image](https://github.com/user-attachments/assets/47be6533-fb49-4bb6-833b-c69839e9ee62)

Then, I needed to create the triangle part where I would place the threads for the cords. I created a new sketch on the side part of the clip, then drew a triangle shape and constrained it to the edge of the clip. This is where I ran into a problem - when I tried to pad this triangle thing for it to match the length of the clip, I got an error "Pad: Result has multiple solids. This is not supported at this time." By googling the error I didn't find an easy solution, but realized that the fix would probably be to kinda "merge" the triangle into the clip. Doing this actually fixed the problem, and I was able to finally pad the triangle thing. I still don't really get why FreeCAD doesn't allow two pertfecly constrained objects to be padded, but after all it worked out for me and I was happy:

![image](https://github.com/user-attachments/assets/633c8597-8b81-4e16-8d0d-215b96f93616)
![image](https://github.com/user-attachments/assets/8c047a66-f834-4596-8df6-a6c2b59d0e3a)

Next, I had to make the threads for cables in the triangle part. This process went smooth, and I didn't run into any errors or problems, so I honestly don't have a lot to comment about. Long story short, I just created 3 rectangles, aligned and pocketed them to make them "void". Then repeated the process with circles and that's basically it. Here are some screenshots I took while working on this part:

![image](https://github.com/user-attachments/assets/e619aeae-8651-4f5b-b3d0-8ed8082022a8)
![image](https://github.com/user-attachments/assets/e677f60e-5656-49b8-be24-82b04d912081)
![image](https://github.com/user-attachments/assets/41a8cdc4-d4da-41c3-8b55-9666c75b291c)
![image](https://github.com/user-attachments/assets/969c2400-a8eb-498f-84ac-69115680e7e2)

Finally, I used the fillet feature on all sides of the cord threads to make them look more nicely, and with that the second object was finished.
![image](https://github.com/user-attachments/assets/20bcbcbf-2bec-4ac7-b7cf-ac64ca38c6bb)
![image](https://github.com/user-attachments/assets/f466ff29-359b-419d-9345-eea0e715c94a)

**OBJECT 3 - unseparatable objects**

As I mentioned above, I think I have some serious issues with the part of my brain that is responsible for creativity. Coming up with two objects that would not fall apart after being fit together was the hardest part of this whole assignment. And surprisingly (or not), I found the solution when I wasn't even thinking about this assignment - I just accidentaly saw the coin box that my younger sister made using a nesquik box and cutting a hole in the lid. I realized that creating a coin box and a coin technically would satisfy the requirements - coin can be fit into the box, and you can flip, shake and toss the box in any imaginable and unimaginable ways and the coin will stay inside.

I honestly feel like this idea is so genious yet so simple, so there's not much for me to comment here. The creation process also went with no troubles. For object A, I just created a box 15x15 cm, and made it void with the walls being 5 mm thick. On the top part, I created a rectangular slot of 25.02 mm by 2.02 mm. For object B, I just created a coin of 25 by 2 mm in a separate document. As you can see, the slot is 0.02 mm bigger than the coin dimensions, and that's like that to make it easier to put the coin inside. 

![image](https://github.com/user-attachments/assets/51c671b2-1db7-4145-9546-63334eaf4616)
![image](https://github.com/user-attachments/assets/6e3baaed-76d7-4483-87a2-d641d7e278cd)

*Object A*

![image](https://github.com/user-attachments/assets/97b5d1d8-96bd-421b-a639-8676070f6962)
![image](https://github.com/user-attachments/assets/179dc0b2-8ab0-4de8-a2a2-0164666d9aa3)

*Object B*

![image](https://github.com/user-attachments/assets/f54a5bde-5795-47a4-bbf5-2313bb42e9b1)

**Conclusion**

It took me about 4 hours to finish this assignment, which I think is kinda scary considering the fact that I only had to create three objects (okay, technically four). I've run into some issues and problems during the process, and sometimes I felt lost in the variety of buttons and functions. However, after Tinkercad, FreeCAD made me feel like I'm actually learning and doing something that actually can be used in the real world problems. Generally speaking, I enjoy 3D modeling, and I think that if I actually devote some time to teach myself all features of the FreeCAD, I'll be able to create some cool and useful stuff with it. Will I actually do that? Probably no. I think that if I'll need to do some complex 3D modeling, I'll find some software that's more capable and is newer. Overall, I think I lied in the intro part and I actually enjoyed this assignment, but I don't wanna do this again (ever (def not in freecad)).

**P.S.**

By the way, it is my birthday tomorrow (Nov. 26). Just wanted to mention this here since it's technically my blog

**P.P.S**

I'm not hinting at anything, but if I got extra credit for my bday I'd be happy

**P.P.P.S**

Really really happy :)
