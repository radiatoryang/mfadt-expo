## I'm Robert, www.debacle.us
- my background is in video games and VR
- I teach here and at NYU
- I've presented / demo'd at a lot of places, mostly in games contexts
- I also curate and help run No Quarter, an NYU games exhibition http://gamecenter.nyu.edu/events/no-quarter/

## MFADT / aesthetics of interaction
- MFADT is not a games program, but we teach games classes... why do you think that is?
- interaction as aesthetic... "roleplaying" / expression
- successful public games are usually:
   - easy to learn / try
   - short round times
   - fun to watch
   - expressive, allow users to "perform" / roleplay
- I'm focusing on games / playful / VR stuff, but the general concepts can be useful for a lot of you

***

# EXHIBITING INTERACTIVE STUFF AT A STUDENT SHOW 101

## 1. IMAGINE YOUR IDEAL INTERACTION / EXPERIENCE?
- approach this like a design problem...
- identify 2-3 different audience "personas", what do they want from you?
- example: Journalist wants images + YouTube embed + "a story"
- example: Employers want portfolio + demonstration of your competence + contact info
- ... hopefully your project has specific domains and you know what those domains want

## 2. PLANNING CHECKLIST

#### How will you run your demos?

for all digital interactives, I recommend:
- auto-startup macros for Windows / OSX, automatically boot-up your app when the OS starts
- code an Attract Mode ("press Start to begin") to signal "beginning" of an experience
- code an idle timer, e.g. automatically reboots back to Attract Mode after 1 minute idle
- code a manual override "restart" button, in case of bugs and freezes
- hide the keyboard during the show
- no live internet... if you rely on data, cache your data or feature an "example" dataset

VR is new and difficult, you should always have someone there
- wipe down HMD with alcohol-based wipes
- coach guests new-to-VR on how to put on an HMD
- have ginger chews / ginger candy for worse-case users
- if room scale, a person should hold the tether for them

#### How will press / media know how to contact you?

business cards advertise you, the artist
- doesn't need to be expensive, but don't be too cheap
- leave at least 1 side more "blank" (whitespace) to write notes on
- leave some near your kiosk
- you need these to have less awkward interactions with grown-ups in grown-up world

postcard flyers advertise your project
- title + "key art" + short text blurb + URLs and social media
- link to project website (buy a domain), keep it simple, test on mobile
- you should have images + a YouTube embed (for journalists)
- if games, look up presskit() http://dopresskit.com/

don't use QR codes in the US
- people won't take you seriously

## 3. SOURCING EQUIPMENT

less equipment is almost always better

if school can't meet your equipment needs, then do what countless MFAs have done before you: run to Best Buy, buy something, take really good care of it, then return it after the show

make sure you get locks and enclosures for any phones / tablets

if possible, fabricate duplicates for any fragile hardware
- 50% chance your hand-soldered arduino thing is going to be destroyed
- using any pressure or flex sensors or servos? 90% chance of destruction
- in general, anything a guest will touch (controllers, mice, buttons, joysticks) has a good chance of being destroyed
