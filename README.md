    .---.      .-. .-.         .--.-.         .-..-.          .-.    .--..---.    . -- . v . -- .
    : .; :    .' `.' `.       : .-: :         : :; :         .' `.  : .; : .; :   \ (<) '.' (>) /
    :   ..-..-`. .`. ..--..--.: `;: : .-..-.  :    .-..-,-.,-`. .'  :    :   .'    \_    .    _/
    : .; : :; :: : : ' '_.: ..: : : :_: :; :  : :: : :; : ,. :: :   : :: : :.`.    .='  / \  '=.
    :___.`.__.':_; :_`.__.:_; :_; `.__`._. ;  :_;:_`.__.:_;:_;:_;   :_;:_:_;:_;    \_o_/   \_o_/
                                       .-. :                                   
                                       `._.'                                   
                                       
# Butterfly Hunt - Augmented Reality Application

Buterfly Hunt is a Marker based Augmented Reality game.  It is made up of a single page application built in Vue, which connects to a seperately hosted Web-AR application, with bespoke 3d butterflies made in blender.

It was concieved of in response to the lockdown conditions imposed across the world in response to the COVID-19 pandemic.  My project team wanted to create an app that would give children access to an activity that they couldn't currently do outdoors, and give parents an engaging activity to ease some of the stresses of new fulltime childcare responsibilities.

We imagined a scavenger hunt, where a parent could hide custom AR markers throughout their home, that a child could seek out and scan with their phone.  Each marker will reveal a randomly selected butterfly, which can be caught and added to the child's collection. 

This was the final project produced on Northcoders Coding boot camp.  The project team members were [Harriet](https://github.com/Harriet-Blundell), [Rob](https://github.com/mauvesky1), [Norbert](https://github.com/mauvesky1), and  [Conway](https://github.com/conwayhub).

This repository is for the Augmented Reality elements of the application, and is written in AR.js, A-Frame, and Javascript. 

View the live site here:  https://butterflyhunt.co.uk/

## The Vue Single Page Application

If you're interested in this project please feel free to check out the github repo for the Vue Front End over [here](https://github.com/Harriet-Blundell/ScavengerHuntAR)

## The Back End

The Back End for this project is a lightweight Firebase Database, with Cloud Firestore authentication measures in place. 

## The User Stories

### AS A PARENT: 
&emsp;👨&emsp;I want to be able to log in and out, and view my own details when logged in.

&emsp;👩&emsp;I want to be able to add my child accounts, manage my child's account and delete my child's account.

&emsp;👨&emsp;I want to be able to have multiple children with seperate profiles on my account. 

&emsp;👩&emsp;I want to easily download and reproduce the markers required to play the game. 

&emsp;👨&emsp;I want to be able to set up a new scavenger hunt for the child.

### AS A CHILD: 

&emsp;👧&emsp;I want to be able to create, view, and customise my profile, with a username and avatar.

&emsp;👦&emsp;I want to have a place to look at my collection.

&emsp;👧&emsp;I want to get positive feedback when I find a butterfly.

&emsp;👦&emsp;I want to be able to catch multiple different types of butterflies.

&emsp;👧&emsp;I want to see a small description/name for the collected butterfly

&emsp;👧&emsp;Upon scanning a marker, I want to add the caught butterfly to collection.

&emsp;👦&emsp;I want to be shown an animation upon catching the butterfly.

&emsp;👧&emsp;I want an interface where I can switch between my profile, my collection, and my camera.

&emsp;👦&emsp;I want to be able to count multiple caught copies of butterflies in my collection, rather than duplicating them.

&emsp;👧&emsp;I want to have an indication of how many more collectables I'm missing.

## Take Her For A Spin!

Please feel free to fork and clone this repo, to run locally, or take a closer look at the code!

### Requirements

&emsp;❗&emsp;To run this repository, you must be using Node JS version 13.01.0 or higher. Check your current version with the command `node -v`.

### Steps for running this project locally

&emsp;✔️ &emsp; Fork and Clone the project down to your local device

&emsp;✔️ &emsp; Download or view the custom markers [over here](https://github.com/conwayhub/markertests/blob/master/Markersheet.pdf)

&emsp;✔️ &emsp; AR.js and A-Frame run directly in html, so no packages need to be installed to run this repository! 

&emsp;✔️ &emsp; cd into the project, and select Go Live

&emsp;✔️ &emsp; Scan the markers with your camera, clicking the screen when the cursor turns green to view the butterfly animations and mark them as caught. 
