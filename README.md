# Angry 50
This is a coursework project from Harvard University`s CS50G.

# Implemented Features:
Mid-Flight Split: Players can unleash a tactical maneuver by pressing spacebar after launching an Alien, but before it collides with anything.

Triple Threat: Upon spacebar press, the launched Alien splits into three separate Aliens, tripling the offensive potential.

Smart Spawning: The two new Aliens spawn at precise angles relative to the original Alien's velocity, maintaining a sense of directional momentum and creating a visually impactful split effect.

Collision Awareness: A clever system prevents splitting after the Alien makes contact with anything, ensuring the maneuver can only be performed in mid-flight.

Advanced Reset: The launch marker responsible for Alien launching doesn't reset until all the Aliens spawned from the split maneuver come to a near-complete stop. This prevents accidental relaunching before the full effect of the split has played out.
