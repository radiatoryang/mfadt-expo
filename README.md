## I'm Robert, www.debacle.us
- my background is in video games and VR
- I teach here and at NYU
- I've presented / demo'd at a lot of places, mostly in games contexts
- I also curate and help run No Quarter, an NYU games exhibition http://gamecenter.nyu.edu/events/no-quarter/

## MFADT / aesthetics of interaction
- MFADT is not a games program, but we teach games classes... why do you think that is?
- interaction as aesthetic... "roleplaying" / expression
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
- disable screensavers!
- auto-startup macros for Windows / OSX, automatically boot-up your app when the OS starts... make it easy for other people to help bootup your interactive thing when they just turn on your computer (otherwise you have to go there every morning to make sure it works)
- code an Attract Mode ("press Start to begin") to signal "beginning" of an experience
- code an idle timer, e.g. automatically reboots back to Attract Mode after 1 minute of no user activity
- code a manual override "restart" button, in case of catastrophic bugs and freezes
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

## 3. EQUIPMENT

if making an installation, you cannot build a "ceiling" (e.g. drape cloth or a wood board over some walls), that violates the fire code and the fire marshall will shut you down

less equipment is almost always better

if school can't meet your equipment needs, then do what countless MFAs have done before you: run to Best Buy, buy something, take really good care of it, then return it after the show

make sure you get locks and enclosures for any phones / tablets / expensive electronics... things do get stolen at shows

if possible, fabricate duplicates for any fragile hardware
- 50% chance your hand-soldered arduino thing is going to be destroyed
- using any pressure or flex sensors or servos? 90% chance of destruction
- in general, anything a guest will touch (controllers, mice, buttons, joysticks) has a good chance of being destroyed

if using any infrared (Vive VR, Oculus Rift CV1 VR, Kinect, LeapMotion, your own IR solution) then be careful where you're pointing your IR LEDs / lasers... this is a big problem in VR, when 2 sets of IR laser sensors end up fighting each other

## TAKEAWAYS

- successful public exhibitions are usually:
   - easy to learn / try at first (if making a "deep" game, you should have a casual "buttonmasher" layer)
   - short round times (5 minutes or less)
   - fun to watch (learn about it by watching others interact)
   - expressive, allow users to "perform" / roleplay, good selfie opportunities
   
- make a special show version of your app / demo
   - if you are making some kind of board game / tabletop game, you may want to create an easy abbreviated ruleset... OR don't even let people play it, just showcase the game pieces in a glass box, and post the rules, and let people imagine what it would be like? treat it like a conceptual sculpture

- think about which audiences you want to reach
   - avoid "Art English" unless that's who you're going for
   - write accessibly, using everyday language

- make it easy for the press to write about you
   - YouTube embed, video is key
   - website with presskit / mediakit with images and text blurbs
   - have a clear story: "I'm gay, and I noticed straight people kept thinking I was straight... so I made an app that tweets I'M GAY to all straight people within a 500m radius and I call it RAIN-BLOW"
