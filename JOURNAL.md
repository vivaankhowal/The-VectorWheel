# The VectorWheel Journal
This is where I track my progress of designing this project.

**Disclaimer 1**: There aren't any 3D files for this project YET, because the CAD isn't 100% finalised and I can't finalise it until I get the funding for the parts.

**Disclaimer 2**: This journal is just all my Stardance journals in one page. That's it.

**Disclaimer 3**: The first few timelapses were recorded with the built-in timelapse feature in Stardance because Lapse was down at the time.

## Lapse Links
(1-4 were recorded with the built-in Stardance timelapse feature) <p/>
5. https://lapse.hackclub.com/timelapse/zN36sTvcJg-F
<p/>
6. https://lapse.hackclub.com/timelapse/jczi4nbVKZ9p
<p/>
7. https://lapse.hackclub.com/timelapse/qBNeQfHCAhFp
<p/>
8. https://lapse.hackclub.com/timelapse/rpubunKt_AFO
<p/>
9. https://lapse.hackclub.com/timelapse/FS9OxUoiHBtn
<p/>
10. https://lapse.hackclub.com/timelapse/gTwme2IFQQ89

## June 24: Started Project

**Total time spent: ~1 hr**

I'm going to be headed to college in the fall, and the campus is pretty big, so I got the idea to buy a OneWheel, but those are very expensive. So I'm going to build one myself.

Today was mostly researching how I was going to pull this off and if anyone else has done this for inspiration. Thankfully some people have.

<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/0639b576-b738-405f-8c5a-887d8798dc87" />
<img width="686" height="386" alt="image" src="https://github.com/user-attachments/assets/ff0e1521-0f90-4ae7-97d8-6736e767f20f" />
<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/1d285754-82b8-48f5-b243-577116c197ef" />

OneWheels consist of a few core components: A hub motor, an ESC, a big battery pack, and some electronic footpad sensors. On top of that, they also have LED strips, a gyro, an accelerometer, and some even have a remote control. Now its time to jump into CAD and just mess around a bit.

I finished a basis for the design. For the tire, I’m going to be using the official OneWheel Pint S Performance Tire. For the frame, I saw someone use aluminum box tubes for the sides of the frame, so we're doing that too. The electronics casing will be made either with ABS or some other strong plastic or some kind of metal. I want to design my own hub motor from scratch (literally starting with a metal coil and magnets) since hub motors for this size are super expensive and very rare.

<img width="1600" height="870" alt="image" src="https://github.com/user-attachments/assets/54a4df8a-dff6-4c27-84fb-ff4b72b3fa54" />

## June 25: Custom Motor Design

**Total time spent: ~1 hr**

Today was kind of just playing around with the dimensions for this motor. I designed a basis for the stator and the rotor for the motor. Measurements need work, but it’s a start. I know that motor tolerances are gonna have to be very tight and cannot be 3D printed, so the plan is to hopefully get these manufactured somewhere else like PCBWay or JLCPCB and have them ship it to me, but there are many parts of a motor.

A motor consists of 2 things: A stator, which is the inner part and the part that usually connects to the shaft and spins, and the rotor which is the outer shell. The rotor is lined with magnets all around in alternating polarity whereas the stator is a very precisely cut metal piece with slots for copper wire to wind around to form coils which generate a magnetic field making the motor spin.

Almost any little dimension (size of the rotor, amount of magnets, number of windings for each coil, etc.) affects the speed and torque of the motor, so this is going to take a while for a perfect motor that I need.

<img width="1000" height="618" alt="image" src="https://github.com/user-attachments/assets/1775964d-e037-499b-8344-7a5621b578b4" />


Also as a bonus, I added grooves to the tire in CAD to make it look like an actual tire.


<img width="1600" height="871" alt="image" src="https://github.com/user-attachments/assets/e360404f-3e87-4c84-9c23-d6a6358dde4c" />

# June 26: Big Mistake

**Total time spent: ~30 mins**

I made a big mistake.

I forgot to check how expensive it actually is to get a part like this manufactured, its around $300 which is WAY out of my budget for this project (like I really had a budget lol but this is way too expensive no matter the budget).

Instead I’m planning on using two 6.5” hoverboard hub motors joined together inside an official OneWheel tire for a custom hub motor. It doesn’t fit perfectly, but I think it’s still workable with some metal adapters or if I change the tire. This was an idea I saw in this youtube video:

https://youtu.be/SdHUSAQd6hc?si=dBqVY03ALT4P_jff

<img width="686" height="386" alt="image" src="https://github.com/user-attachments/assets/ea56ec09-6ab6-4f99-b205-f73297b8e130" />

# June 28: Finally some luck

**Total time spent: ~2 hrs 30 mins**

Idk why I keep doing this, but the hoverboard motors won't work because the tire that I chose has an inner diameter way too large to fit the hoverboard motors, so I would have to design some kind of crazy metal adapter and I tried finding a different tire, but couldn't find one with the right dimensions for sale, so I decided to switch back.

After looking at a lot of videos and research, I found a company called Spintend that sells not only actual OneWheel style hub motors, but also the ESC, electronic footpads, a fuse, and some other parts as part of a bundle costing around $400. 

That is a very good deal for some parts that are very difficult to find.

https://spintend.com

<img width="1470" height="830" alt="Screenshot 2026-07-25 at 2 50 09 PM" src="https://github.com/user-attachments/assets/ca99d00f-4558-42d8-b606-bcae785bbdca" />

I took the dimensions listed on their website for the components and modeled mockups in CAD so I can design my board based off of those dimensions.

<img width="1600" height="872" alt="image" src="https://github.com/user-attachments/assets/634745da-6ced-4f26-acad-4b48a1678fee" />

Also started modeling some of the basic parts like the wooden footpads and the electronics housings, and refining the design a little bit more to make it actually look like a OneWheel. The bundle covers pretty much all the electronics except the batteries. Eventually I settled on making my own battery pack since custom battery packs are way easier to make than custom motors. I asked AI to help me figure out this battery pack, and it told me that I should use 21700 cells in a specific configuration. Not entirely sure how that works, but i'll figure it out.

<img width="1600" height="870" alt="image" src="https://github.com/user-attachments/assets/9de77668-6354-42d9-af23-3dd34e2038e8" />

## June 29: Battery Pack

**Total time spent: ~1 hr**

I finally figure out the battery pack, and let me explain how this works:

A battery pack is essentially a ton of batteries spot welded together to combine their voltage and capacity in a specific way to reach the voltage or current requuirements of a circuit. Batteries can be wired together in 2 ways: series and parallel. Series adds up the voltage whereas parallel adds up the capacity. For example, if I have two 6V batteries with 10Ah capacity and wire them in series, I will get 12V since the voltage adds up, but the capacity will remain 10Ah. However if I wire them in parallel, the voltage will stay at 6V, but the capacity will increase to 20Ah, so same voltage, but longer runtime.

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/addf24b9-5dde-4c74-8879-add35b646878" />

Battery packs use a specific notation when wiring:

**(number of batteries in series) s (number of batteries in parallel) p**

Example: If I have a 5s2p battery pack with five 3.7V batteries and a capacity of 1Ah each, that means 5 batteries wired in series multiplied by 2 rows wired in parallel which outputs 3.7 x 5 = 18.5V and a capacity of 1 x 2 = 2Ah total.

<img width="274" height="285" alt="image" src="https://github.com/user-attachments/assets/bc21f7ab-13f4-451d-a65c-aee807bce0ed" />

For my OneWheel, I decided to use a 14s2p battery pack of 21700 battery cells, so 28 cells in total. I had to split up the config a little bit to make it fit in the OneWheel, but I made it work in the end.

<img width="1384" height="900" alt="image" src="https://github.com/user-attachments/assets/cc3a4ea1-f9e5-4508-b17d-afd3ebaaa79f" />

## July 2: CAD Cleanup

Today was mostly cleaning up the CAD model. I replaced the hub motor mockup I made with a legit model I found online with similar dimensions. I added a latching button as an on-off switch on the side of the OneWheel as well as a barrel jack connector to charge the board.

I also added LED strips to the front and back of the board for nighttime riding as well as some detailing work on the tire. I changed up the colors of the board as well to get a better idea of exactly what it will look like in real life.

<img width="1600" height="872" alt="image" src="https://github.com/user-attachments/assets/621fe8c2-4936-4880-8e08-48ed24a27b1d" />

