## Design Pillars
With the updated requirements for the website/app, here are the 4 new design pillars to focus on with these updated features:
1. Usability - Can Users Accomplish Goals Efficiently
As stated by Jordan, now we will be focusing on the UX elements of the website, and how the performer's side of the website will look different from the audience's side. So they need:
+ a colour palette for the performers side that switches when the audience side is toggled.
+ The two colour palettes should be similar to one another to keep the app consistent and not drastically different in colour, perhaps having buttons that are blue and backgrounds that are yellow for performers can then have it switched for the audience where buttons are yellow and backgrounds are blue.
+ However, with these colour changes it is important to make sure all buttons and text are still visible to the user so that one set of users do not struggle compared to the other.
Jordan is also looking for a dark mode variant. So they need:
+ An icon of a sun and a moon on a toggle to showcase light and dark mode. Once either is selected, the user should be able to see a clear difference in the brightness of their screens, but all buttons should still be visible and usable.

2. Findability - Can Users Locate What They Need
Jordan is looking for distinct iconography for the app as well as aesthetics that hold up under glaring sunlight and dim night streets. So they need:
+ A sun and moon toggle to change from light mode and dark mode to be on every page.
+ Maybe even a blue light toggle to help with staring at screens at night.
Here is a link for ideas:
https://www.pcmag.com/how-to/how-to-stop-blue-light-from-disturbing-your-sleep

+ Make a settings icon to encompass these toggles so it is easier for viewers to make these selections and it is not bombarding the screen.
Aesthetics that will hold up under glaring sunlight:
+ Deeper shades with high contrast text.
+ No pure tints or colours.
+ Reduce graphics to simple designs that can be distinguished immediately
Here is a link for ideas:
https://ux.stackexchange.com/questions/134227/what-are-the-best-practices-to-design-user-interfaces-that-are-going-to-be-used

Aesthetics that will hold up under dim night streets:
+ Dark backgrounds with deep colours that are not too bright.
+ Text colours that are very visible in contrast to the background.
+ Buttons must be easy to spot on the screen even with the darker shades.
With these changes to help with visibility, it hopefully will be easier to locate what users are trying interact with in any weather or time of day.

3. Desirability - Does it Create an Emotional Connection
He wants energetic visual tones and color themes. So they need:
+ A vibrant colour palette with yellows, oranges, and blues.
Palette ideas:
![[Colour Palette Energy.png|191]]![[Colour Palette Seaside Spark.png|227]]

+ There needs to be a dark mode variant as well.
Palette ideas:
![[Dark Mode Bridge.png|235]]![[Dark Mode Crystals.png|236]]

Hopefully with these colours and their deeper shades for dark mode it will feel energetic and exciting for a music application but also not overwhelming since these users need to do things quickly and not be distracted by visuals and graphics.

To help visualize:
https://colorffy.com/dark-theme-generator?colors=%23b33a17&success=%237dff95&warning=%23ffbc5e&danger=%23ff8080&info=%2387d1ff&primaryCount=6&surfaceCount=6

4. Accessibility - Can Everyone Use It?
It is really important for all users to feel of this application to feel seen and excited to use their side of the app, whether that be performer or audience.
+ It is important for all users to be able to see all icons and buttons at all times, so the colours must not blend into one another too much. That will help people who cannot read small text that is also a colour that blends too much into the background.
+ For users that are sensitive to light, the dark mode should feel usable and understandable while also having no colours that are too flashy and make a dark mode too bright.
+ The light mode should be seen clearly anywhere and cause people to not have to squint.
+ Perhaps making the light and dark mode toggle more clearly on the page instead of in settings will help make it easier to change modes to facilitate usage.

## User Assumptions
### Personas
https://www.figma.com/design/CBDJlBv3oRMqR5HyivBiCh/CART-498---Personas?node-id=0-1&t=uPawuG8eLCgMdpF5-1

---
## List of Features
1. The colours of the website should be bright and vibrant like the references.
2. The colours should change noticeably but subtly enough when switching between the performers and audience side.
3. Create a toggle with a sun and moon for light mode and dark mode.
4. Create a settings/more icon where users can find a blue light toggle on and off.
5. Reduce graphics to simple designs that can be distinguished immediately

## Detailed Features

### Hypotheses
1. The colours of the website should be bright and vibrant like the references.
To be able to attract users that want their performances to be found on apps that are as exciting as their performances will be, the colours and their combinations must draw the users in. It must be exciting and energetic, wile not having too many colours that then end up making the user experience feel overwhelming.

2. The colours should change noticeably but subtly enough when switching between the performers and audience side.
When the toggle is moved between performer interface and audience interface, it be able to differentiate between the two, the colours must be different, but not completely different because it should still feel like the same app. So the colours must be similar but slightly different with what parts are coloured what.

3. Create a toggle with a sun and moon for light mode and dark mode.
I am not sure if I want this in the settings or just on the main interface yet, but there should be a toggle of a moon and sun for dark and light mode. Whenever the toggle is moved it should change the colours of the interface completely to fit the light and dark mode aesthetic (maybe have an automatic option that changes mode depending on time of day). 

4. Create a settings/more icon where users can find a blue light toggle on and off.
At the bottom of the page where there is the navigation bar, an icon either saying "more" or "settings" should be created to open up to new features that are too much to be on the main interface, but are still important to have on the website.

Inside this settings icon should be another toggle where users can turn on or off, the blue light feature which will help users with their eyesight at night or in situations where they need to use screen and do not want it to affect how long they have to be staring at their screens.

5. Reduce graphics to simple designs that can be distinguished immediately
I am thinking of making my icons on the app and navigation bar to be a lot more basic and simple to make it easier to understand no matter the changes of colours on the website as well as the changes of modes.

### Experimentation
#### Obsidian Canvas User Flow:
[[CART 498 - Week 4 User Flows.canvas]]

##### Direct Images:
![[Week 4 User Flow.png|700]]


#### Figma Wireframe:
https://www.figma.com/design/AULXAATqRi79ffFKxfQdQS/CART-498---Wireframes?node-id=0-1&t=MmAAUFdwUr2QsaHL-1

#### Reception from Google Forms
##### What I should improve and fix for the next prototype:
###### Home page struggles:
- [ ] Make the performer/audience toggle more visible and click instead of drag to change which side the user is on.
- [ ] Not sure whether to click live set or location first from starting screen.
- [ ] Navigation is clear but the options are not.
- [ ] Text is too long to read on home page.
- [ ] Cut back on a lot of text explanation. Or have text hidden in a tutorial section.
- [ ] The home page feels a bit redundant to contain that much information, it might be useful for there to instead be a little information button (i) at the corner that the user can see at any time in case they need to see the information again. Maybe then you can move the audience/performer button to the main map as well and make it easier to switch between the two.

###### Find Location page struggles:
- [ ] The pin feels more like another performance and not the users performance being shown.
- [ ] "Live Set" and "Location" go together but the navigation bar makes them two active actions separately.
- [ ] Streets are too long to be able to find a location just by its radius.
- [ ] Being able to search directly by name or by live set duration would be useful too.
- [ ] There could also be an option for performer notes, like "across from the cafe."
- [ ] Few options can make it simpler but if there's a lot of locations it would be harder.
- [ ] Easier to simply be able to select "Current location."
- [ ] Many streets have the same name in different locations, I'd suggest using ZIP/Area codes.
- [ ] Not super clear how to switch to user mode, I think maybe adding a button somewhere that is available when looking at the map could help.

###### Find Location pop-up page struggles:
- [ ] Unsure what value setting the radius offers.
- [ ] Want a search option before publishing and going live.
- [ ] More information such as time duration clock.

###### Live Set page struggles:
- [ ] Could not find live countdown timer.
- [ ] There isn't a indication of the set time and if the extended time works so when hitting live, there is nothing indicating of the duration.
- [ ] Everything kind of blends in together. Everything has the same weight/inference for the live tip jar and timer.
- [ ] Extend time needs to be bigger.
- [ ] Need a verification pop-up so that people do not end their live sets accidently.

###### WiFi related struggles:
- [ ] Not clear how losing WiFi affects the app.

###### Live Set ended pop-up struggles:
- [ ] Not clear where to go or what to do when the live has ended.

###### Other struggles:
- [ ] Accidently started a live set without going through all the steps.
- [ ] Biggest problem at the moment is that everything has the same weight. No dynamic font sizes, very complex icons. There's a lot of noise and it unclear what I can do unless I really focus.
- [ ] More mobile-friendly. Larger text as well as icons; helps with legibility and accessibility. Maybe make some text into overlay popups that make it explicitly clear when something has begun or ended. My biggest issue overall is with the form. Specifically, when I have to indicate something for my rating, is it positive or negative? Like my rating can be good but I can interpret the indication in two ways: Either it indicates what I thought was good, or it can also indicate why I didn't give it a higher rating. It isn't clear.
- [ ] Fix the layout as when you click the button on the main page, the layout shifts a bit.


## Prototypes (1)
https://www.figma.com/design/RFCzjvyUYwn62Drgkl47B0/CART-498---Prototypes?node-id=0-1&t=PJo6MTGVMgnGpbvr-1

### Goal of the Prototype
Fix as many issues as I can from the last prototype feedback to see if the app is now more usable. I want to change how my prototype looks visually to help users understand it better and feel more excited. I also want users to be able to find the new toggles for the different modes of the app. I am hoping to see if they can do all these steps:
1. Switch between performer and audience interface and see the changes of colour, so that they can differentiate between the two just by colour.
2. Find the light and dark mode toggle and see the difference.
3. Use the settings icon to find the blue light toggle and turn it on and off to see the difference.
4. See if the reduced graphics of my icons allow them to be more findable and more understandable.

I hope that with this prototype, users feel like the issues they had with my last prototype have been mostly resolved, as well as feel more engaged with the prototype now that there is colour and different modes to change the colour's presentation.

### Medium
The medium I used to make my prototype was completely through Figma.