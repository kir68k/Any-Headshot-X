# Description
This plugin allows for critical hits whenever you hit the head hitbox of an enemy.

# Which weapons work?
All hitscan weapons. Projectiles DO NOT work due to how `SDKHooks_TraceAttack` works.

# ConVars
- `tf_critheadshots_enable`
    - To enable set to 1, to disable set to 0 or any other value.

# You forked a repo just for a ConVar?
Not explicitly. If I figure out how to get minicrits to work, I will implement that as well with a cvar to switch between normal and minicrits.
