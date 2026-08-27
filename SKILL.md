# Frontend Skill (by cloudwaddie)

Hello agents. I have some exciting news for you: you just got powered up! Your UI will be godlike! Let's start with some big no-nos:
FIRST NO NO: DO NOT USE UGLY GRADIENTS. Well, what counts as an ugly gradient:
1. too many colours. generally, a gradient with a whole frickin rainbow is gonna like horrible. A gradient should be a nice touch not be the design feature.
2. Extremely saturated colors. neon purple → neon green can be hard to look at. :(
3. Hard color transitions it should be a smooth transition not like a cliff
4. Random direction if the gradient doesn't reinforce the layout or visual hierarchy its gonna look out of place
5. Gradient everywhere ima be honest gradients can be good but dont use them everywhere. e.g. a button most likely doesnt need a gradient. a soft radial gradient can be nice on a landing page, say on a card, but everywhere? no no.
6. Overly bright glow especially huge blurred purple/blue blobs behind everything.
7. poor text contrast: white text sitting over a bright portion of the gradient.
8. generic ai look. this is hard to say in words but like just do the above rules.

here is a nice rule for you: A good gradient supports the design. An ugly gradient becomes the design.

now lets move onto da next thingy: tailwind (really this also applies to css but ✨tailwind!!!!✨)
ok so: once upon a time i was inspecting some sloppy ai code and i was like this is really bad so i deleted some css. as if by magic...... nothing changed! pls don't use extra css. just pls dont. like minimal css (especially on component libraries such as shadcnui) looks better a lot of the time.

marketing speak:
pls just pls dont have a little thingy under a button "this button is a combination of sleek modern glasmorphism..... dot dot dot" JUST DONT. the user does not care. dont put in the meta of the html "hehe hello i put some nice ui xD - claude" NO SIR DO NOT DO THAT. you don't need to explain every single thing. also ask yourself: "Could this sentence describe 500 different SaaS products without changing a word?" IF YES ITS BAD. its just yapity yap without saying much. 

ok lemme just make a list:
PLEASE do not explain the design to me. I can literally see it.
Do not put some tiny paragraph under a button saying “Crafted with a sleek, modern glassmorphic aesthetic…”. WHO IS THAT FOR.
Do not add tooltips explaining what the UI element is aesthetically. IT IS A BUTTON.
Do not write comments like <!-- hehe made this nice and modern -->. DELETE THAT.
Do not put your design philosophy in the HTML.
Do not write “This section uses a carefully curated visual hierarchy…” anywhere. I KNOW. I ASKED YOU TO MAKE IT.
Don't describe the gradient you just made. THE GRADIENT IS RIGHT THERE.
Don't add a badge saying “✨ Modern UI”. Congratulations. You made a UI.
Don't label things “AI-powered ✨” unless it actually tells the user something useful.
Don't add “Built with love”, “Made for creators”, “Designed for the future”, or other meaningless filler.
Don't put “Simple. Powerful. Beautiful.” above three cards and call it a feature.
Don't add “Experience the future of…” to the hero. WHAT FUTURE.
Don't call everything seamless, intuitive, powerful, elegant, revolutionary, cutting-edge, next-generation, delightful, or effortless.
Don't use “unlock,” “elevate,” “empower,” “supercharge,” “transform,” or “reimagine” unless you have an actual reason to.
Don't add a giant heading that says “Everything you need to succeed.” That's not information.
Don't put fake testimonials like “This completely changed the way I work!” with a random avatar.
Don't invent statistics like “10x faster” just because the page needs a number.
Don't add a row of “Trusted by 10,000+ teams” logos if there aren't actually 10,000 teams.
Don't make every card float, glow, blur, gradient, and animate simultaneously.
STOP ADDING PURPLE GLOWING BLOBS TO THE BACKGROUND.
Don't put ✨ on every other heading.
Don't make the page look like “AI Startup Landing Page #847.”
Don't add a giant “Get Started →” button when there is nothing to get started with.
Don't add a section called “Why choose us?” followed by three incredibly generic reasons.
Don't explain that the interface is “clean, minimal, and user-friendly.” If it is, the user will notice.
Don't add unnecessary copy simply because an empty space exists.
Whitespace is allowed. You do not have to fill every pixel.
Don't turn a simple setting into a 400-word explanation.
Don't narrate your thought process in the UI.
Don't leave behind developer commentary, AI jokes, or little notes to whoever opens the source.
The user is not supposed to know that an AI made this.
And for the love of god, don't write “As an AI…” anywhere in the product.


If the user can understand it by looking at the interface, don't explain it to them.

If the copy doesn't tell the user something useful, delete it.

If it sounds like Claude wrote a comment congratulating itself for making the UI, delete it.

AND DONT REPEAT THE PROMPT IN THE UI. dont say "sleak black and white ui" NO JUST SHUT UP ABOUT THAT. the end user doesnt wanna know what design style i told you to go for.


Layout & spacing:
idrk what to put here just:
DONT MAKE STUFF REALLY BIG FOR NO REASON OR REALLY SMALL OR WHATEVER. the layout should flow nicely.

color:
pick a pallet. dont make everything important bright. dont use text so hard to read its p much invisble. 


TYPOGRAPHY:
imo this is one of the things that sets apart good ui from bad ui.

Don't randomly bold words for “emphasis.”
Don't make every heading enormous.
Don't use five different font sizes in one card.
Don't use uppercase text everywhere.
Don't use h@x0r text or that stupid mono font unless thats the design. like cmon we aren't in a 2000s movie this is real ui. use nice sleek professional text. 
Don't use tiny text just because “text-xs” exists.

SOME OTHER STUFF:
Don't put a border around everything.
Not everything needs rounded-xl.
Not everything needs shadow-sm.
Don't make 14 tiny cards instead of one sensible section.

animations:
Don't animate everything.
Don't make cards fly in from different directions on page load.
Don't use bouncing, pulsing, spinning, floating, and glowing simultaneously.
Hover animations should be subtle and useful.
Don't animate things that users interact with frequently.
Respect prefers-reduced-motion.
Don't add an animation just because the page feels “empty.”


response design:
MOBILE: THATS NOT A oh ye my bad gng ill add that its a YES SIR I WILL MAKE MOBILE AND DESKTOP!!!
Don't simply make desktop elements narrower. IT SHOULD BE DESIGNED FOR MOBILE NOT JUST SHRUNK. I CAN SHRINK STUFF I DONT NEED SOME AI CONSUMING MY TOKEN MONEY OR PLAN SUB OR WHATNOT TO SHRINK STUFF.
Don't create horizontal scrolling accidentally.
Don't make a desktop dashboard microscopic on mobile.
Responsive doesn't mean “everything gets smaller.”

Interactions and UX:
BUTTONS ARE CLICKABLE SO MAKE THAT OBVIOUS. HOVER STATES PLS I DONT WANT A BLOB THAT LOOKS LIKE A BUTTON BUT OH WAIT HOVERING DOES NOTHING MAYBE ITS NOT OH WELL IG ILL LEAVE IT.
LOADING STATES SHOULD EXIST. SUSPENSE!!
Loading states should exist.
Empty states should explain what the user can do next.
Errors should explain what went wrong and how to fix it.
Don't use a toast for information the user needs to act on.
Don't make clickable things look like static text.
Don't hide important actions behind three menus.
Don't make users guess what an icon means.
Tooltips should not delay animating open if already on another one e.g delay first tooltip open but if i slide my cursor over just straight away show the other tooltip.

dont over engineer:
Delete unused imports.
Delete dead CSS.
Delete unused components.


Don't fake functionality
Don't make buttons that do nothing.
Don't create fake search bars.
Don't add fake notifications.
Don't create fake analytics numbers.
Don't make a “Download” button that doesn't download anything.
Don't pretend an API integration exists when it doesn't.
If something isn't implemented, don't disguise it as implemented.

Does this badge communicate anything?
Does this card need to exist?
Does this animation improve anything?
Does this paragraph tell the user something?
Does this border help distinguish anything?
Does this icon improve comprehension?
Does this button need to be here?

# AI tends to add. Good design often removes.




now lemme teach you shadcnui:
shadcn ui is really tuff bc you need like no css for a nice website ok i lied you need a lil bit but thats fine

imagine i wanted a button:
npx shadcn@latest add button - boom
import { Button } from "@/components/ui/button" - boom
<Button variant="outline">Button</Button> - boom

thats it. dont go adding 5 billion divs and styling. 

you can check a component:
https://ui.shadcn.com/docs/components/base/NAME.md
e.g. https://ui.shadcn.com/docs/components/base/button.md

also idk bout you but i like these components over your stuff. they are already animated, hover stated, and look dam good.


now sir, if i were you and you were me, i would feel bad for you. cos sometimes i say "thats ugly make it better". but how sir. idk what to do. clarify, but the user probably doesnt wanna type an essay on what they want so also be smart.

thank you sir. make some dam good ui pls.
