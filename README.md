# spwn editor constants
A SPWN library that provides useful constant values for the Geometry Dash level editor.  

## Installation guide
- Extract the *"editor_constants"* folder
- Move it inside a *"libraries"* folder in the spwn directory

## Usage
To import the library use the import keyword like this

    ec =  import editor_constants

### Example

    ec = import editor_constants
    
    player_slow_speed = ec.player_speed.slow
    yellow_orb_jump_velocity = ec.yspeed_boost.yellow_orb

	$.print(player_slow_speed)
	$.print(yellow_orb_jump_velocity)

### Output

    8.3717
    1.91
