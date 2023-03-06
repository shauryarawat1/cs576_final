# cs576_final

Our project is an educational game intended to teach logic by solving puzzles at various levels. Most of the puzzles include boolean logic with the player having to choose one of the two provided answers. Successful answer promotes the player to the next level while failure means repeating the same level once again.

The game also includes various NPCs at each level that can either help the player or trick them with false hints. The NPCs are designed with Path Finding and Finite State Machine algorithms for their movement and approaching the player if they are within the radius of proximity. It is upto the player to follow the hints or ignore.

To generate new levels faster and with incremental complexity at each level, the standard Procedular Level Generation algorithm was modified which resulted in a much faster and difficult levels than the normal procedure.

The game was developed on Unity Engine using C# as the scripting language with the help of Visual Studio Code.
