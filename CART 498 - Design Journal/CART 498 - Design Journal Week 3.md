## Design Pillars
With the updated requirements for the website/app, here are the 4 new design pillars to focus on with these updated features:
1. Usability - Can Users Accomplish Goals Efficiently
Tess is now looking for a a button on the active set screen to extend the set time. So they need:
+ A separate screen for when the performance has been published and is actively live.
+ Within that screen should be a button that says clearly "extend +15 min." and every time it is clicked it adds and extra 15 minutes to the performance time.

Jordan, the product manager, wants a way to quickly see the active countdown timer, current tip jar, and an "end set" action. So they need:
+ On a new page to keep the location and importance of buttons separate, there will need to be big bold numbers that actively count down from the time set by the performer.
+ There will be a live tip jar that will be continuously filling as the audience's side of the map allows them to give the performer tips.
+ At the end of the screen should be a large "end set" button that when clicked immediately takes away the pin that was created on the map.

Claire, the city liaison, has informed that it is prohibited to display exact GPS coordinates and to instead have a proximity radius. So they need:
+ On the map screen, instead of searching up exact coordinates the performer will have to find one street name close to them that can be looked up and the pin will be placed there.
+ Once the pin is placed, the audiences' side will be able to see the street and see that it is just a proximity radius. It will then be there job to find exactly where it is on there own either from hearing the music or seeing the crowd, or information being shared by others but not by the app itself.

Liam is now wanting the active set interface to work entirely offline once launched, with timers connecting locally on the device. He is expecting clear offline indicators and a recovery state if connection drops. So they need:
+ Once the performance is published, on the screen with the actively live set, there must be a visible icon that indicates when the app is offline, but it never asks the user for cellular data, it just continues to function.
+ When there is a connection drop, the app will indicate it, but all buttons will stay usable and all screen will still be able to be navigated since the app should work with and without WiFi the same way.

1. Findability - Can Users Locate What They Need
With separate screens for each important feature, it will be a lot easier to find exactly what each performer is desiring to look at and interact with while on stage.
+ The extension button should be clear and indicate how much time will be added onto the set as well as a visual of the increased time, this button should also be able to have a "go back" button in case there is a misclick. All this should be immediate on the page.
+ On the active live set screen there will need to be a very clear countdown timer as soon as the performance is live and the time of the performance is published. 
+ The tip jar must be clearly stated perhaps with an icon to indicate what it is tracking. 
+ The end set action should be at the bottom of the screen and immediately cause the pin to disappear on the map.
+ Because of the GPS restrictions the proximity radius should be very clearly stated so that the audience is aware as well as the performer that the location is not exact, and that the audience themselves will have to do their own individual finding.
+ With the offline function, it should be clear when the user is on or offline with an icon.
+ When the connection drops the user should get a quick notification, but the application should still work as normal since it should work on and off WiFi.

1. Credibility - Do Users Trust Your Product
With the clear buttons on the performers side of the app, it should directly translate to the audience immediately so that everyone is on the same page without any issues. As long as everything works smoothly and everything is connected there should be no problem with trusting this app is showing completely live feedback.

For the GPS restrictions, as long as it is clear to the audience that it is an approximate radius, it should allow for privacy as well as quicker location pinning because of the less specific location.

To make sure the WiFi connection changes does not change the usability of the application, the refreshing and finding the WiFi connection or disconnection should be in the background, keeping the app working as usual and giving the much less cumbersome experience.

1. Usefulness - Does the Product Solve a Real Problem
If performers are restricted by time, by WiFi connection efficiency, and by accurate GPS locations, they need quick informative buttons to click on that create big important changes to inform their audience nonverbally, they need easy to read performance information. They need WiFi connection refreshing to not affect anything on the app to keep everything smooth. And they need their audience to know where they are by following city laws. With these new features added to the app, thing should run smoother for the performer and therefore the audience.

## User Assumptions
### Personas
https://www.figma.com/design/CBDJlBv3oRMqR5HyivBiCh/CART-498---Personas?node-id=0-1&t=uPawuG8eLCgMdpF5-1

---
## List of Features
1. Create an active set screen with a button for extending set time by 15 minutes each press.
2. Create an active Live Set screen with a countdown timer, current tip jar, and end set button.
3. The map should no longer be a specific location and instead just one street and a radius of how far it is from that street.
4. An icon indicating if the app is online or offline
5. A notification when WiFi goes down to indicate the change, but no change to the website itself.

## Detailed Features

### Hypotheses
1. Create an active set screen with a button for extending set time by 15 minutes each press.
Separating each important feature with a page that can be navigated by the bottom menu would be important. Here with the active set after the performer has clicked publish, there can be a button that says "extend by 15 minutes" that gives them the ability to extend the set time every time they click it. This can help them focus on this button only on the screen. (This can also be in the live set screen).

2. Create an active Live Set screen with a countdown timer, current tip jar, and end set button.
Making another screen for the live set info would help performers see all the current information about their set very easily. They will have a large countdown timer that will be dictated by the time they chose when setting up the live. There will be a current tip jar with an icon that shows how many tips they are getting live. and at the end of the page is a button that says end set that when clicked will completely take the pin off the map. All that will be left is the performer to see the live set screen info that will have paused.

3. The map should no longer be a specific location and instead just one street and a radius of how far it is from that street.
When the performer is met with the map page, the search bar to create the pin should be less specific and only allow for one street to be searched for. Then they can select how big of a radius they want to have the pin be at, so that the audience does not know exactly the location, but knows the general area.

4. An icon indicating if the app is online or offline
There should be a WiFi symbol on all the pages indicating that the performance is live, so that the user knows when the application is on or offline.

5. A notification when WiFi goes down to indicate the change, but no change to the website itself.
Because the app must work completely offline, the transition from on to offline if there is spotty connection should be smooth, maybe a quick dropdown notification stating the WiFi is down and will try to find connection again. But the application's usability should not change.

### Experimentation
#### Obsidian Canvas User Flow:
[[CART 498 - Week 3 User Flows.canvas]]

##### Direct Images:
##### Start
![[Week 3 User Flow Start Image.png]]
##### Middle
![[Week 3 User Flow Middle Image.png]]
##### Top portion connections
![[Week 3 User Flow Top portion connections Image.png]]
##### Top portion connections in depth
![[Week 3 User Flow Top portion connections in depth Image.png]]
##### End
![[Week 3 User Flow End Image.png]]


#### Figma Wireframe:
https://www.figma.com/design/AULXAATqRi79ffFKxfQdQS/CART-498---Wireframes?node-id=0-1&t=MmAAUFdwUr2QsaHL-1

## Prototypes (1)
https://www.figma.com/design/RFCzjvyUYwn62Drgkl47B0/CART-498---Prototypes?node-id=0-1&t=PJo6MTGVMgnGpbvr-1

#### User Form:
https://docs.google.com/forms/d/e/1FAIpQLSe4v9RrtWdvQZqZt289FBfkT_A4Y_gI3djCOD9nPovJsp6W8g/viewform?usp=publish-editor