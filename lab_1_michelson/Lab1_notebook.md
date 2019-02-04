# Lab 1 The Michelson Interferometer
##### Ryan Schmidt - 23407159
##### Giulio Sucar Pregnolato - 46117131

## Introduction
The Michelson interferometer is a tool that splits light beams into two paths of similar distance that can be altered as desired. This tool allows for experimentation with interference patterns, which reveal specrtal information about different light sources (in our case, a HeNe laser, a sodium lamp and a white light). 
The experiment consists of setting up and tuning the interferometer in order to observe interference patterns, then experimenting with different light sources and collecting data across a span of path length differences. 

### Day 1

#### Finding fringes
First we needed to align the mirrors, we used the HeNe laser and the TV screen. Then we adjusted the mirrors till we could see an interference pattern on the screen.

As we adjust the mirror horizontally we see a vertical interference pattern, and when we adjust vertically we see a horizontal pattern. The pattern has the highest spacial frequency when they are not aligned well and when they are aligned the pattern looks like it has a smaller spacial frequency.

After talking to the professor we realized that we should be using the lens in front of the laser, it spreads the beam out so we can see more of the fringes.

With the smaller fringes, we could change the angle and phase of the frequencies by moving the alignment of both mirrors, as different patterns formed when the light from the two mirrors were not coinciding in the photodetector. 

### Day 2 Jan 21 2019 14:00

#### Aligning mirrors
We used the technique that the lab tech taught us to align the mirrors:
- remove the lens from the workbench
- cover one mirror and align the other by looking at the dots on the beam splitter
- repeat for other mirror
- align hole on paper with stand with laser between mirror and beam splitter
- insert lens between laser and beam splitter and adjust until beam is through hole in paper again

Insert picture of interference pattern

#### Finding Coherence length and zero path length difference

First we need to get the mirrors to where they are almost the same distance from the beam splitter so we can see the interference pattern from the sodium lamp. First we used the apt software to home the stage and then put it approximately in the center of its range of motion. then using a ruler we found that we needed to move mirror 2 closer to the beam splitter and realign. then we turned on the sodium lamp, added the lens to the camera and the screen in front of the bulb. I then adjusted the stage till i could see the lines with the most clarity. We observed that as the mirror moves the lines transition from curving up, to flat, to curving down. So I am guessing that when they are flat is close to the ZPL. This is about 11.6mm with our current setup.

After talking to the lab tech we found that we don't need the lens when using the sodium lamp or white light. Also we should be at the ZPL when we observe the most contrast between the peaks. We found this to be around 12.2 mm. We ran the matlab script moving at 0.05 mm/s centered about this point to see if we were close to the ZPL. Then we should take data running at 0.001 mm/s for a long time to measure the coherence length. We will not have time to do it this week so we will next week

Insert Plot

#### Redoing last weeks work

Last week it seems like we didn't save our data properly so we had to retake the calibration and index of refraction data. To calibrate we used the HeNe laser and took a set of data in matlab with 0.01 mm offset and 0.001 mm/s speed. which will be used to calibrate our data later on.

Then we put the vacuum chamber in front of M2 and used the vacuum pump to pull out the air. Then we collected data for 120 seconds while letting the air back in.

Insert Plots 


### Day 3 Jan 21 2019 14:00

### Finding coherence length and frequencies of sodium lamp
To explore the behaviour of the sodium lamp, we must take a long span of data, in order to observe the coherence length (by fitting the slow decay in amplitude and fitting it) as well as the 2 main frequencies composing this light (by observing the average wavelength and the period of  beats formed due to 2 similar wavelengths composing this beam). To achieve this, one fast span was taken to better position the mirror 1, and another slower data set was taken to obtain quality data that can undergo a fourier transform without generating noise due to insufficient sampling.

Details of tada acquisition:
mid position: 12.1
speed: 0.005
span: +-1
