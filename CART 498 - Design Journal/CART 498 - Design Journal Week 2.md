## Design Pillars 
With the pivot to focusing strictly on the performer side of the website for now, the design pillars must shift from the design pillars mentioned in [[CART 498 - Design Journal Week 1]]. Singling in on the 4 most important design pillars for this new focus on the website will be:
1. Usability - Can Users Accomplish Goals Efficiently
As stated before, the performer is looking to have very fast and easy experience on this app therefore, all buttons and instructions should be clear, bright and straightforward.

As Tess, the musician consultant, stated, because of the business of performers, their section of the website must take only a few taps to be able to go live. So they need:
+ A search tab to look up where they are located on the map, or just an automatic tracking sensor like google maps. Once found drop a pin.
+ Then when the pin is clicked on there should be a window that pops up restating the location maybe and asking the performer how long the concert should be.
+ Once the timer is set, on that window should be a publish button that the bottom. Once the publish button is clicked it should still have a double checking feature to see if the user really wants to publish so that there are no accidental publishes.

As Liam, the dev, stated, there needs to be fixed duration presets. So they need:
+ When the window pops up, there should be a dropdown under "time" that lists presets of 30min, 45min, 60min.
+ There should also be an extension button if the performance goes on for longer, that either the performer can set before the performance goes live, or that the audience can toggle to help other people stay in the loop with the timing. Kind of like how people can report delays on the metro with google maps.
+ After the performance is over, after the timer is completely done plus the extension if needed, the pin should disappear automatically.

2. Findability - Can Users Locate What They Need
If there is an initial toggle button of who is using the website, either performer or audience, the website will have slight changes that will occur that will benefit the user. 
Focusing on the performer side:
+ the map must be right in their face so that they can locate themselves and start the process of going live.
+ The search bar for location must be right on top of the map like google maps.
+ Any pop ups must be automatic and done by clicking on locations.
+ The spaces the user is able to add information into about the performance should be quick and easy and get straight to the point.
+ Lots of presets and dropdowns with premade responses.
+ Finally a big legible publish button at the bottom of the pop up.
+ The text stating if the performance should be published or not should be brief and only keep the key importance; where it was a misclick (No) or time to publish (Yes).
+ Then the performer should be able to see their pin and when clicking on it it should have all the information they just added.

3.  Accessibility - Can Everyone Use It?
As stated previously, the app should have very clear instructions or instructions that can easily be found. It should have some sort of vocalized navigation possibility that can be toggled on and off if desired or required. Like a GPS usually has. Alerts should also be able to have some sort of buzz or sound alerts. But as someone who may not be able to think of all things that cause apps to be accessible for everyone or not, user input will be very necessary for this part.

For the performers accessibility:
+ They should be able to easily locate themselves on the map without having to waste too much time.
+ Perhaps having voice to text could speed up the process.
+ There should be a place on the website where you can click it and it can give you a guide of how to use the website.
+ Dropdowns will help with accessibility
+ Presets will help with accessibility and speed

4. Usefulness - Does the Product Solve a Real Problem
As stated before, the problem that I am trying to fix is that performers and audiences need a much easier solution to finding one another, the audience desires to see a performance, and the performer desires a crowd. If there is an easy solution to find one another then both parties get what they are desiring.

The problem that is solved for the performers must be:
+ They need a platform that will allow them to connect with their audience through live time performances.
+ What they see on their end must be perfectly translated to the audiences' end.
+ If the performers are in a rush they should still be able to set up and publish their live performances quickly and easily, with easy to read windows and clear boxes to fill out.
+ The performance time should be accurate to what is happening live, it must have automatic features that take away the pin once the performance is done, and/or allows the audience to interfere with the scheduled time to help other fans out.

## User Assumptions

### Linsey Hanford (songwriter and guitarist)
Age: 23
Education: Concordia Alumni
Occupation: part-time performer, full-time guitar instructor
Location: Montréal QC, Canada
#### Personality
+ Adventurous
+ Easy-going
+ Easily distracted
+ Honest
+ Charismatic
#### Brief story
I just finished my bachelors degree at Concordia University in Electroacoustics. I am not a very popular artist yet, but I would like my part-time job of being a performer to one day be a full-time job of mine. I do not like to rush so I am more than willing to take things slow and take my time and I hope my audience feels okay with that.
#### Goals
+ Become a full-time performer
+ Increase my audience
+ Be found out by strangers
+ Keep my schedule organized and efficient
+ Form a full band
#### Frustrations
+ I am easily distracted so I need to be able to have some way of telling my fans where I am and what I am doing, for how long, very swiftly so that I can keep my mind busy with the rest of my performance set up
+ I want to easily be able to locate venues that I can perform at and I want to easily be able to book the venues through one website and not each individual venues' website
+ I always forget to let my friends and family know when I am finished a set, so I want it to be evident when I am done performing

---
### Bill Welfare (singer)
Age: 43
Education: Graduated Masters student at Imperial College London
Occupation: Full-time singer
Location: London, England
#### Personality
+ Quick-witted
+ Efficient
+ Short-tempered
+ Team-spirited
#### Brief story
I have been a graduated student of Imperial College London for over 15 years now and my Masters in Opera has served me well. I am now a singer under a very well known and reputable label. My label expects me to be efficient and punctual and always prepared for my fans. I cannot lose my reputation.
#### Goals
+ Reach the charts
+ Understand my audience better so that I know where to perform and where will get me the biggest audience
+ Get my scheduling and organization of my performances done with speed and efficiency
+ Impress my label
#### Frustrations
+ My life is one big rush, so I want all my responsibilities as an artist to be accomplished immediately without much effort
+ My label pressures me to speed up my scheduling of venues to get tickets able to be purchased as soon as possible
+ I am stressed about my label dictating my life and decisions, but I am not famous enough to give up on this label and go solo

---
## List of Features
1. Home page of a map with a search bar at the top for performers to find themselves
2. Create a pin once the user clicks on their location
3. Clicking on the pin will cause a pop-up window listing time and publish
4. Have presets to keep the experience as fast as possible in a dropdown
5. Have an extension button or toggle of how much longer the performance is going on for and have the audience able to manipulate it as well
6. Have pin automatically disappear when the event is over

## Detailed Features

### Hypotheses
1. Home page of a map with a search bar at the top for performers to find themselves
Because of the need for performers to easily locate themselves and thus their audience as well, we need to implement a map with a tracking feature or just a manual click to find locations. It is clear that once a performer can be located, the rest is a lot easier to organize.

2. Create a pin once the user clicks on their location
Having a visual pin once the location is clicked on gives user feedback and outcome that will allow the performer to make sure they have the right address for their fans. Therefore, the pin should be placeable manually or could be immediately placed if the address is searched up on the map.

3. Clicking on the pin will cause a pop-up window listing time and publish
With the added visual of the pin, being able to physically interact with the pin and that will cause an outcome will create a better user flow. The pin being clicked on should create a window pop-up for performers to be able to add in information of their performance. Performers will be able to find themselves and start going live in seconds.

4. Have presets to keep the experience as fast as possible in a dropdown
Performers need to go live as quickly as possible, so there must be presets already there for them in a dropdown menu to help speed up the process. That means performers will not have to think twice and just click. Therefore, they can spend more time setting up other things and not worrying about performance information.

5. Have an extension button or toggle of how much longer the performance is going on for and have the audience able to manipulate it as well
If the performance goes on longer than expected or intended, the audience needs to know. There should be a button that allows the user to get a dropdown menu of how much the performance is extended to. The feature should also work for the audience in case the extension is very unexpected, so that the fans can inform other fans. Maybe the button or toggle will need to change depending on how structured most performances are.

6. Have pin automatically disappear when the event is over
To make it easier for the audience to know when their favourite performer is still playing or not, once the original time and perhaps the extended time is finished, the pin should automatically disappear to make the audience aware that the performance is fully over. It should have a live feature for fans to inform fans so that performers do not need to spend extra time informing.
### Experimentation
#### Obsidian Canvas User Flow:
[[CART 498 - Week 2 User Flows.canvas]]

#### Figma Wireframe:
### Results
To be determined...

