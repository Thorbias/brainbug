---
title: "Ascaso Steel Duo PID mod v3"
published: true
img: /assets/images/ascaso-v3-mod
tags: [Coffee]
description: "Inspired by a reddit post I moded my espresso machine and created a guide a long the way."
---

## Intro
Give credit where credit is due - my work and instructions are based on [this reddit post](https://www.reddit.com/r/Ascaso/s/GC7wgwMkaL) by u/DamnFineCaffeine. I just did my mod slightly different, took pictures along the way and wrote it down in this post. So a big shout out to u/DamnFineCaffeine! For better orientation I will directly reference his schematic drawing which compares the water flow before and after the mod:

![Schema](https://i.redd.it/sh4nfs12zgth1.jpg)
*1. schematic overview by reddit user u/DamnFineCaffeine*

This mod though is fully reversible and no hose or other parts will be cut/changed. For the hose we will use a new part and the original hose will remain as it is. Actually we just add one extra piece and one extra hose - that's it!

## Motivation
Two years ago I bought me a Christmas prestent - an Ascaso Steel Duo PID v2 and a Eureka Mignon XL. I love this machine! The looks, the haptics the fact that it is a thermoblock and not a boiler machine which gives me a perfect coffee witin 5 minutes. But one thing bothered me all the time: I got inconsitent results. Sometimes I would have 19g espresso in my cup for a cappuccino and some times it was 28g (some days even worse). Although I took my time and dialed it in at 9g in and 22.5g out. So I started to grind 4-5g in the morning and throw it away. Didn't help much as my Eureka was a time based grinder. So I got my self an upgrade: Fiorenzato Allground Sense. It is a beautiful grinder with grind by weight and helped me to get 18g of coffee powder in my double basket - every signle time. But even with this my results did vary. And than I found this blog post at reddit and it suddenly all made sense. The flow meter of my beloved Asacso Steel was measuring the inflow but the OPV did mess with the total amount of water that would eventually reach my cup. After thinking it through for a few days I decided to give it a try. Spoiler alter: It is amazing and not too hard to do on your own (the fiddling in the little space of the machine aside).

## Getting to work
Alright, let's get to work. At first we need to get all items we need for the mod. Than we will prepare the machine to be ready to do the modification. And than of course we will mod the Asacso Steel Duo PID.

### Materials and tools you will need
Make sure to have everything at hand that you need:
#### Materials
* [Y-Fitting](https://amzn.eu/d/0avndX0k)
* [silicone hose 5/8mm diameter (inner/outer)](https://amzn.eu/d/0gYYsWWi)
* [hose clamps](https://amzn.eu/d/043C2csE)
#### Tools
* screw driver
* needle-nose pliers
* tweezers
![Tools]({{ page.img | relative_url }}/ascaso-v3-mod-11.jpeg)
*2. tools I used to get the mod done*


### Prepare your machine
At very first you need to unplug the machine from electric power! Don't open the machine before you reomved the plug. Take out the water reservoir, empty it and put it aside. Than you need to take off the top plate of your Ascaso which is the cup heater. You just have to unscrew two screws at the back of your machine and than you can carefully pull the plate backwards. Be aware that there is a cable connected to the plate to heat it up. So don't just rip it off ;-) You can easily uplug the cable from the heating pad on the bottom side of the plate. Than place the top plate aside.

Now you are ready to get started.

### Giving you an overview of the components inside your machine
Be prepared to see a mess ;-) I was suprised by the density and amount of cables when I opened the machine. So here is a brief overview of what you will see:
1. OPV return hose
2. Steam return hose
3. Flow meter
4. Cup heating power line (which you should have detached)
5. Water pump inflow hose
6. Steam inflow hose
7. Plate separating water tank and inner electronics

![Overview]({{ page.img | relative_url }}/ascaso-v3-mod-0.jpeg)
*3. looking inside the machine*

You will be working on (1) OPV return hose and (3) Flow meter and you need to unscrew (7)

### Getting a little more space to work inside your machine
As everything is packed in very little space you will most probably have a hard time getting your hands in there. At least I had. And as I am also not a professional espresos machine engineer I didn't dare to remove to many parts. So I just unscrewed the plate which seperates the water tank from the inner electronics. There is one screw inside the machine (you can see it on the overview tagged with 7) and one on the outside. That's it. Than you can carefully pull up that plate a little bit and than it should get loose. On the right side of it there is some more electronics attached. Just leave it be and move the plate a bit more to the backside of the machine. This should give you just about enough room to work inside the machine without breaking your fingers.

### Set up the Y-fitting
Ok let's have a closer look at the water flow. On this picture you will see the hose returning the water from OPV to the water tank (1). And the hose which runs from the flow meter to the water pump to actually feed the water into the heating and finally resulting in your espresso (2).

![Current-Flow]({{ page.img | relative_url }}/ascaso-v3-mod-1.jpeg)
*4. original water flow*

Now let's prepare the Y-fitting:

![Y-Fitting]({{ page.img | relative_url }}/ascaso-v3-mod-2.jpeg)
*5. preparing the Y-fitting*

On the picture you see the Y-fitting with (1) the return of the OPV where we will attach the original hose comming from the OPV. At (2) you need to attach the new hose - don't cut it yet, just attach it and secure it with a hose clamp. The other end of the hose will finally be attached to the flow meter outflow. And at (3) you see the flow towards the water pump where we will attach the hose comming out of the flow meter.

### Re-wiring the OPV hose
This is the moment where you will change your machine ;-)
Unplug the the hose comming from OPV from the drain which leads into the water tank - seen on picture 5 (1). Than plug it onto the Y-fitting and secure it with a hose clamp:

![OPV-Hose]({{ page.img | relative_url }}/ascaso-v3-mod-4.jpeg)
*6. re-wiring the OPV hose*

### Re-wiring the flow-meter out hose
We have reached the hardest part of the mod: rewiring the flow-meter hose which runs to the pump. Let's take a look at this picture to get some orientation:

![Flowmeter]({{ page.img | relative_url }}/ascaso-v3-mod-5.jpeg)
*7. re-wiring the flow-meter hose*

(1) hose running from Y-fitting to water pump
(2) hose comming from OPV
(3) new hose - still in full length
(4) flow meter

(2) and (3) have been already done in the previous steps. We focus on (1) and (4).
The hose you see attached to the Y-fitting (1) was attached to the flow meter (4) before. So try to get your hands on the flow meter and pull the hose off. Maybe a needle-nose pliers or tweezers helps here. Than you need to find a nice way around all the other cables and the stuff in your machine and attach it to the Y-fitting and secure it with a hose clamp. You will probably have to pull it downwards where it runs around the steam heating and push it upwards close to tha plate infront of the water tank. Keep an eye on the hose so that it does not have any kinks or knots.

### Take a deep breath
You are half way through! Great job so far! relax your finger and take a deep breath.

### Attaching the new hose to the flow meter
This may now seem like a step backwards but for me it was easier to detach the new hose form the Y-fitting to have more freedom to do this step:

![Y-Fitting-Prepared]({{ page.img | relative_url }}/ascaso-v3-mod-6.jpeg)
*8. Y-fitting with OPV in and water pump out*

Than we will attach the new hose, still in full length, to the flow meter. Make sure to have the hose clamp on the hose already. Than you need to fiddle a bit as there is really not much space. A tweezer could be helpful to slowly move the hose onto the flow mter out. Use the pliers to get the hose clamp in position. Now carfully fiddle the rest of the new hose on a kink free route to the position where the OPV backflow lead to the water tank. This picture should give you some orientation:

![New-Hose-Attached]({{ page.img | relative_url }}/ascaso-v3-mod-7.jpeg)
*9. New hose attached to the flow meter*

(1) hose running to the water pump
(2) hose comming from the OPV
(3) input for the hose comming from flow meter
(4) flow meter out with attached new hose
(5) hose comming from flow meter

### Final step: cut the hose and attach it
We are almost there! Now it is time to cut the new hose! Don't be too greedy here, give it some play but not too much. Than attach it to the Y-fitting and secure it with a hose clamp:

![New-Hose-Y-Fitting]({{ page.img | relative_url }}/ascaso-v3-mod-8.jpeg)
*10. New hose cut and attached to the Y-fitting*

Now stow the Y-fitting where you find a good spot. I just moved it a little bit down deeper into the machine below the water tank plate. Here you see a picture from the front towards the water tank:

![Y-Fitting-Stowed]({{ page.img | relative_url }}/ascaso-v3-mod-9.jpeg)
*11. Finally the Y-fitting is stowed inside the machine*

(1) hose comming from OPV
(2) hose running towards water pump
(3) new hose comming from flow meter

### Closing
Now it is time to get everything back in place and close the machine. Start with the water tank plate and shove it from above into its compartment than attach the screws. Than attach the heating plate calbes - or leave it out if you don't want the heated cup plate. And get the top plate of the machine back in place and insert the last two screws. Plug it in and gibe it a test run - your done!

### Enjoy your espresso, cappuccino, latte macchiato
You made it! Congratulations on your v3 mod for your Asacso Steel Duo PID. Now it is time to enjoy your favourite specialty cofee.

![Enjoy]({{ page.img | relative_url }}/ascaso-v3-mod-10.jpeg)
*12. Enjoy your coffee*

### Final thoughts
After the mod you should dial in your espresso again. For the last two weeks I measured every shot from the machine and it was giving me very constant results. I measured the amount of espresso with a scale and two cups as I am almost always making two cappuccino for my wife and me. I dialed it in at 18g in and 45g out for two cups. The variance was +/- 2g reaching from 43g to 47g. I think that is a prett nice result compared to where I started.

Being a barista is a craft, and coffee is a natural product. I am by no means a barista, but I love good coffee. But results vary as beans are diffent and a lot of factors influence your result. A professional barista with professinol equipment can handle that. But I had to get rid of as many varying factors as I could. And still the beans age, the remaining coffee powder in the machine has influnce on your result and air humidty, the presure you put on the tamper - and maybe even the moon ;-) all influence the espresso you get. But after this mod I get the best espresso I can get at my home and I couldn't be happier - enjoy your coffe :-)
