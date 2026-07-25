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

# June 26: Big Realisation

**Total time spent: ~30 mins**

I made a big mistake.

I forgot to check how expensive it actually is to get a part like this manufactured, its around $300 which is WAY out of my budget for this project (like I really had a budget lol but this is way too expensive no matter the budget).

Instead I’m planning on using two 6.5” hoverboard hub motors joined together inside an official OneWheel tire for a custom hub motor. It doesn’t fit perfectly, but I think it’s still workable with some metal adapters or if I change the tire. This was an idea I saw in this youtube video:

https://youtu.be/SdHUSAQd6hc?si=dBqVY03ALT4P_jff

<img width="686" height="386" alt="image" src="https://github.com/user-attachments/assets/ea56ec09-6ab6-4f99-b205-f73297b8e130" />

# June 28: Diamond in the Rough

**Total time spent: ~1 hr**

