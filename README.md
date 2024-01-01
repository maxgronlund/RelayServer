# Simplifying Multiplayer Game Development

We're working on a project aimed at simplifying the process of creating multiplayer games.<br/>
Our focus is on providing a straightforward relay server and a client protocol that helps maintain consistent game states across multiple players.<br/>

### Who is it for?
The project is for game developers that want to create multiplayer games.<br/>

### What it does 
The framework ensure a deterministic outcome on all player clients.<br/>
When a player perform an action, that could be move a charachter,  and action is created and send to the relay server that pass it on to all the clients so they can perform that action.
If and when an action results in a race condition rules for how to solve it is in place so the outcome is that all clients ends up in the same state.


