
# Final project

In view of the current labour dispute conditions, the final project is no longer mandatory; an alternate option to submit a [paper](paper.html) is  also available.

Additionally, you may wish to create projects within smaller groups, rather than everybody contributing to a single project. I will assess contributions according to scale. 

[Project plan in Google Docs](https://docs.google.com/document/d/18WcE7htm6pOg-tiATDiLHA6p9mKLNJMtcEYSmV14Br4/edit)

## Some design questions

Here are a set of questions that may help you come up with a design proposal for the project. Mainly these are questions specific to the interactive/VR nature of the medium; in addition most themes in film production are also applicable. 

These questions may be filtered according to a project theme, or considering them may lead to the development of a theme. Overall these should form a unity, or a multiplicity with a centre. Also, as a result, an appropriate division of expected work will likely arise.

### Interaction

- Where does it sit between the spectrum of a fixed narrative arc to a completely open sandbox?
- Goal oriented or open-ended?
- Fixed time or interactively-paced?
- If there is narrative-by-location, how do you lead/attract the immersant through key points?
- What is the overal tone of the experience (what primal emotions, physical and mental states are elicited, what kind of activities does it resemble, what kind of attitude is required)?

- What devices are used?
	- Only headset tracking
	- Keyboard, Joystick, etc.
	- Leap motion (hands/fingers/pointy things), Kinect (color / depth / skeleton), microphone, etc.
	- others?

- How does an immersant navigate?
	- None -- you can only observe from a single fixed point
	- None -- but you are transported by cuts or continuously (e.g. Senza Peso)
	- Path -- you can only move on a fixed path, but you can control the speed (e.g. [Way to Go](http://www.a-way-to-go.com))
	- Jump/cut -- e.g. look at a location for long enough and you will jump there; or teleport somewhere
	- Walking (running, jumping)
	- Driving (cars, boats, planes, spaceships, robots, riding animals etc.)
	- Flying/swimming
	- Other?

- What kinds of actions can be taken in the world? (Almost anything can be made modulable)
	- In specific locations vs. wherever you are?
	- Actions may have conditions: location, timing, presence of another agent/object, etc.
	- Actions modulate self, agencies, world, ...
	- Play with anticipation, engagement, surprise, revelation, ...

### World-space

- Is there a sense of up? 
	- Things like a ground plane, physics of gravity, and visual references (buildings, trees, rooms etc) will anchor the sense of "upness". Take care to place the user at an appropriate height above ground (by default the space is measured in meters). 
	- The absence of gravity, ground planes, and well-oriented familiar objects will diminish the sense of "upness", lending instead a sense of space that could be non-terrestrial deep space, deep sea, microscopic space, mathematical or abstract space.

- Open or enclosed space? 
	- Enclosed spaces are living environments, caves, dungeons, jungles, tunnels, tubes, vessels etc. Care must be taken to make sure navigation is limited within the enclosed space. There may be partitions between spaces (doors, portals, holes, etc.)  In VR, getting scale correct is extremely important. Enclosed spaces can be comforting, but also claustrophobic. Mazes & labyrinths, narratives of hiding, searching, escaping.
	- Open spaces are deserts, fields, mountain plateaus, the sea (on the surface or below), roadways, the air, deep space, abstract space. Open spaces can be more challenging to fill; it takes effort to ensure they do not primarily convey emptiness (unless that is the goal). If the space is freely navigable, how do you ensure there is something worth experiencing in any direction or location? Some experiences use "procedural generation", which means using an algorithm to generate content wherever the traveller wanders. Some simply repeat content. Most however give the visual impression of open space (via skyboxes for example), but actually limit the range of navigation to stay within certain boundaries, such as walls, cliffs, shores (the island is a very common motif), or some life-threatening danger. Narratives of exploration, journey, loss.
	- Combine both: an open space with entrances to enclosed spaces, such as buildings or caves (e.g. Dear Esther, but also Minecraft). Narratives of discovery, quest, complexity. 

- 'Set design'?	
	- Depends greatly on freedom of navigation; the more free the immersant, the more it becomes architecture rather than scenography. 
	- Consider paths, affordances, balance, hierarchy, scale & proportion, symmetry & asymmetry, unity, rhythm & emphasis, densities, directions and radial balance, form & function etc.
	- Static objects are cheaper than dynamic ones.
	- Open spaces may require terrain-generation.
	- Human-scale or other? 

- Scene by space?
	- Are there “scenes” or scene-like regions (even if you only produce one in the prototype, you can map out more in the documentation)
	- Strange geometries (e.g. portals, worlds-within-worlds such as in Technolust, etc.)

### World-behaviour

- Any kinds of mechanics in the world? 
	- Physics of solid objects -- shapes, masses, frictions, motors and joints
	- Physics of fields, particles and volumes -- attractions, winds, explosions, smokes and clouds, water (difficult), etc.
	- Appearances & disappearances
	- Changes of color, texture, lighting, sounds, etc., 
	- Weather, day/night, disaster (e.g. quake), machines (working or broken), anything dream-like
	- Events, repetitions, rhythms, polyphonies (think Eisenstein, and visual music)

- Any agencies in the world?
	- Machines & Flora -- grasses by texture, trees by simple geometry, machines by via physics or algorithmic motions
	- Robots & Fauna -- mainly by motions that suggest intention: sudden changes of direction, responsiveness to nearby environment, etc.
	- People/characters (or people-like things) -- difficult to even get close to [uncanny valley](http://en.wikipedia.org/wiki/Uncanny_valley), never mind overcome it; but voices & videos are one way, non-realistic avatars are another. Simplistic logic/AI?
	- Multiplayer. Avatars can be quite abstract yet still convey social presence.	

### Appearance

- Is there a self-image?
	- What does it look like? (How to avoid a sense of alienation?)
	- Co-located with the immersant (i.e. look down and see a body)
	- 3rd-person viewpoint, e.g. typically behind and above
	- If using Leap, how do hands appear? Only hands or full body?

- Realism
	- Some things are easier than others to make look reasonably realistic. Most things human or animal are very difficult. Realism also in terms of physics, lighting, sound. Scale and appropriateness of materials. Avoiding noticing polygons in geometry, flatness of texture, etc.
	- How to blend elements of the real world into a virtual space? 
	- Incorporate real-world images, footage, audio? Video can be inserted as 2D screens within the 3D world. Chroma-keying can be used to remove the frame, but it will still look flat. Audio recordings can be incorporated very easily, and tend not to break presence as awkwardly (). 
	- Non-realistic elements do not necessarily weaken immersion/presence at all.
	- [Non-photorealistic rendering](http://en.wikipedia.org/wiki/Non-photorealistic_rendering): cel/toon shading (cartoonlike), sketch/watercolor etc., designer-centric/Bauhaus/minimalist etc. (e.g. AntiChamber, White Mask Experiment), digital aesthetic/TRON-like (e.g. Fract), glitch (e.g. Memory of a Broken Dimension), game nostalgia (e.g. Dumpy, Proteus), etc... 
	- Fantasy, antirealism, hyperrealism, psychedelia, etc.

- Geometries
	- Basic non-solids: points, lines, planes.
	- Basic solids; cubes, spheres, tori, capsules, cones, tetrahedra, etc.
	- Solids (meshes) imported from files (possibly including bone-based animations)
	- Meshes modulated or generated algorithmically.
	- Complex curved surfaces: NURBS, isosurfaces. Mathematically-driven.
	- Particles & simple clouds.
	- Porous volumes & complex clouds (expensive, not easy)
	
- Light & lighting, and post-processing effects
	- Story by lighting, stark, noir, horror, abstract, monochrome, manga, schematic, etc.
	- Navigation by unusual lighting/material (e.g. Devil's Tuning Fork, Unfinished Swan, White Mask Experiment)
	- Easy: low number of light sources; point, directional and spot lights. Simple homogenous fog. Plastic-like materials.
	- Fakeable but expensive: shadows, glows (bloom), ambient occlusion, diffractions, crepuscular (god) rays, cloud-like volumes, reflections, water surfaces, depth of field blur, etc.
	- Opaque materials are easier. Reflective materials are possible. Very transparent/translucent is fairly easy, but weakly transparent/translucent is trickier. 
	- Impossible views, illusions, etc.?
	- Head-up display (HUD) or other overlay? Very game-centric or "terminator view"

- Sound/music?
	- Spatiality
		- located/directional (depth/direction cues as you approach it, even Doppler effects), 
		- personal (e.g. breathing, walking, internal monologue),
		- omnipresent ambience
		- reverberation
		- omnipresent non-diegetic sound/music
	- Continuous sounds and event sounds
	- Voices
	- Adaptive music/sound (responding to state and events in world, even location)
	- Recorded sounds (and samples and instruments) vs. synthetic sounds and effects
	- Image-sound correlations and disjunctions; Michel Chion's l'Audiovision (seen [http://monoskop.org/images/6/6d/Chion_Michel_Audio-Vision.pdf](here)) is a significant reference
	
## Experience Design in Games

We can draw inspiration from [The Art of Game Design](http://www.amazon.ca/The-Art-Game-Design-Edition/dp/1466598646) ([seen here](http://www.sfu.ca/~lws2/summercamp/Art_Game_Design.pdf)). Although this book *is* oriented toward games in particular, the approach it takes is broad enough that most elements can be applied to experiences whether game-like or notgame-like. Written by one of the world's top game designers, it addresses game design holistically through a set of questions drawn in concurrent perspectives, or *"lenses"*, gradually building up a map that looks like this:

![The Art of Game Design](http://www.gamasutra.com/db_area/images/feature/3934/image002.jpg)

You can also get the lenses on your [phone](https://play.google.com/store/apps/details?id=com.schellgames.deckoflenses).

## Assets

Here are some places where free 3D models can be downloaded. Depending on what your intended use for the project is, pay special attention to the licensing terms of these models -- this is intellectual property.

- [Google 3D Warehouse](https://3dwarehouse.sketchup.com/?redirect=1)
- [3D models for free](http://tf3dm.com) 
- [Turbosquid](http://www.turbosquid.com/Search/?KEYWORD=Free)
- [Exchange 3D](http://www.exchange3d.com/Free%203D%20Models/cat_35.html)
- [3DVia](http://www.3dvia.com/search/?search%5Bquery%5D=free&search%5Bresults_per_page%5D=12&search%5Bsort_order%5D=Rank&search%5Bfile_types%5D=1)

For Max/MSP/Jitter, the best format is *Collada* (".dae" file extension). Jitter can also import OBJ (".obj" extension), and might also be able to import other formats. Here's an example patch for quickly checkout out whether a downloaded 3D model works (copy the text below, and in Max choose File -> New from Clipboard):

<pre><code>
----------begin_max5_patcher----------
696.3ocyV98aaBCDG+YxeEm3YVD+H.M6ons2llzjl1aSSQNXOhaM1Y1llzU0
+2msAZHqERRaWWegHewb99943ty2NwyekXGQ4CuG9N34c6DOOmIqAu10d9Un
cELjxsM+BQUEgq8CZ9OMYm1Y+yBwU.RJp4XXKUuF1F.p..E.3.3WAvugqH2n
5dMFkSJL608twsF2fzEqo7xkRRgtIlhmkNML.hisOiRCs+jZV.+n8cnX2oKV
c46hR57tReCi3r2YYU8pULhhhI8OPdcEkyHZmxh5hBIQYDHRSE7Chj38QRX6
i6CiF+22MFeKp0cNOzZ7tISrOBdlj9qDDFnb.AeTvXHLBDR3Ke3SvOolP3LA
b1ENxlj0CvI4C.33gA74fxnvYtSKN6+NK+VsjC50TEH39iPolb+7dPJd1.PJ
5Lgz+B4VQTJTI4AxEwoUKsIk6IQyAouYCoQo992KpGqbLKxp84NPjG1UP7Xb
X9Ihg3GUzQufhVZpWdpxsWwQR5XxM+UWtbxVyA+.0dIUO0llmhkzqIvhZ5RF
UoIbHZXHDbLPzzFtqMwr7wPQxYV.bHJheYQQIaZAphHQvBsjtQfgHXASTbEy
NuZXjXd2kkrkVeUKImLfZqIBGszH9MFfpDXBaTRTgLva2woPymGW3XQyjkgX
P1qNCzhxx8yGefLo1QkGUaw4c89GdBP59AIRymdZhbIgiZ6wG9bj8KbahsBI
COZSgUHd4Il0ybLIMZrjdzyJomzS8Nu6tjyec4UW7YseHRThZYQmxZaRA6iQ
LQoob28T5sm3C1yZJFS38ygXpxlVwCOk9Til4uohl7SHZxdSwljWsnI8Dhln
mXzz7QMZylqIRUqKcAhoh9RgztLOvsjxaV57n4BNWS61u69E9HooHUapPsyt
rkY6tnogqusWujWSaamXN46l7G.Tw2CJ
-----------end_max5_patcher-----------
</code></pre>
