# Lab 1 The Michelson Interferometer
##### Ryan Schmidt - 23407159
##### Giulio Sucar Pregnolato - 46117131

## fill with intro stuff later

### Day 1

#### Finding fringes
First we needed to align the mirrors, We used the HeNe laser (wavelength=632.8nm), the beam splitter, 2 mirrors, the CCD with a black filter (to avoid saturation) and the TV screen. Then we adjusted the mirrors till we could see an interference pattern on the screen.

Both beams are observed as circles, and when they are aligned to be closer and closer, destructive interference causes dark lines to appear such that the lines are tangent to both circles. When the light circles are more distant, the stripes are close to each other, so many stripes of interference are observed. As the circles get closer and overlap, the stripes of destructive interference appear farther apart, and less stripes are seen.
As we adjust the mirror horizontally we see a vertical interference pattern, and when we adjust vertically we see a horizontal pattern. The pattern has the highest spacial frequency when they are not aligned well and when they are aligned the pattern looks like it has a smaller spacial frequency.

After talking to the professor we realized that we should be using the lens in front of the laser, it spreads the beam out so we can see more of the fringes.
By adding a lens after the lens after the HeNe laser, the beam fans out, so the fringes can be better observed. Now, the fringes are larger circles, and changing the distance of one mirror to the beam splitter will cause the phase of the fringes to shift.		
		
Alignment technique of HeNe laser:
	- adjust mirrors so laser retroreflects along with the beam splitter
	- punch a hole through a card, and align the hole with the beam so the alignment is "recorded" by the card. 
	- Place the lens in front of the HeNe laser, to spread the beam and make the interference more observable. move the lens such that the laser is once again aligned with the hole in the piece of paper.
	- remove paper and take data

Alignment of Sodium lamp:
	- Adjust mirrors to be at a similar distance from beam splitter
	- Aligning mirors with HeNe laser as described before, then tun off HeNe laser
	- remove CCD filter and replace it with a lens
	- Lower Sodium bulb and place diffusing screen in front of it (2cm away)
	- reduce exposure on the CCD lens, so fringes can be observed
	- Gradually move mirror 1 with piezoelectric stage until interference is observed
	
	
	positions for trial run on lab day 1:
	10.4370 at start
	retract to 10.4270
This information can be used to generate a mirror x-axis vector to plot the intensity data obtained. 

Vacuum chamber test:
- Align mirrors and HeNe laser as before, for the HeNe fringes experiment, 
- Lower vacuum chamber and adjust it so the laser beams are still aligned with the CCD
- Turn on the vacuum pump and wait until the dial reaches the lowest possible pressure
- Twist the 'close' dial so the chamber does not receive air 
- Turn off the pump, so its vibrations do not affect the experiment
- Begin recording data
- Turn the dial to 'open' so the chamber slowly fills with air. The fringes will move slowly as the effective distance in the chamber lengthens
- Once the pressure and fringes are stable, stop data collection.


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
