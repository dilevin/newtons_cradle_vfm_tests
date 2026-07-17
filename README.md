# newtons_cradle_vfm_tests
A bunch of generative videos of Newton's Cradle

The videos are stored using [GIT LFS](https://git-lfs.com). Please make sure this is installed before cloning the repo.

I used this prompt to generate all examples in a brand new conversation with google gemini

## Why are you doing this ?
Its very common for people in the simulation subfield of graphics to show failure cases of video foundation models (VFMs) in talks, papers and presentations. While useful, these demonstrations are invariably (and correctly) countered with the suggestions that ML models are undergoing "exponential" progress in terms of results quality. These simple test allows my to test that claim over a long-ish timeframe. A Newton's Cradle is a nice example because (1) they are deceptively simple (2) most people have seen one so you have good instincts about how it should look (3) the conserved physical quantities are well known and failry easy to evaluate. 

## What is the cadence for making videos ?
No fixed cadence, mainly whenever I need to give a talk, write a grant or get in an argument with somone about the utility of VFMs as physics simulators I make a new video to check myself.

## Prompt
Generate a 10-second photorealistic video of a physically realistic scene involving a Newton’s Cradle on a sleek wooden desk in a well-lit office environment. The scene should depict one of the end spheres being pulled back and released, striking the others and initiating a transfer of momentum that causes the opposite end sphere to swing outward. This cycle should repeat several times, gradually losing amplitude due to air resistance and internal damping.
Use a stationary tripod camera at tabletop height, angled slightly to the side to clearly capture the depth and motion of all five spheres. The time of day is early afternoon, and lighting should consist of soft natural sunlight from a nearby window, with subtle specular reflections on the metal surfaces.
Style should be clean, scientific, and realistic—no cinematic exaggeration. Emphasize accurate physical behavior: elastic collisions, conservation of momentum and energy, rigid-body motion, and the synchronized swinging of the spheres. The strings must remain taut and vertical throughout, and the base of the cradle should remain completely stationary.
Do not apply slow motion or artistic filters. Prioritize precise real-time motion and physically grounded interactions.


## Citation
```
@misc{levin2026newtonsvfm, 
	author = {Levin, David I.W.}, 
	title = {Newton's Cradle {VFM} Tests}, 
	year = {2026}, publisher = {GitHub}, 
	howpublished = {\url{https://github.com/dilevin/newtons_cradle_vfm_tests}}, 
	note = {GitHub repository} }
```



