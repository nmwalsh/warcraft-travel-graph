# warcraft-travel-graph
Creating and traversing the World of Warcraft travel graph with Amazon Neptune and Gremlin


## In progress:

- Dedupe certain vertex numbers
- Add edges for special vertices 

Notes:
zeppelin and boat trips have different durations in each direction.
Horde:
	org>uc 1:40
	uc>org 1:30

	org>gromgol 1:15
	gromgol>org 1:30

	uc>gromgol 1:40
	gromgol>uc 1:42

alliance:
	rut'theran>auberdine 1:40
	aubderine>rut'terhan 1:30

	auberdine>menethil 1:15
	menethil>auberdine 1:30

	menethil>theramore 1:40
	theramore>menethil 1:42


## Credit:

Source images in `data/` sourced from [Allakhazam Wiki](https://wow.allakhazam.com/wiki/Category:Flight_Points_%28WoW%29).
