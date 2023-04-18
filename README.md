# RabbitEvents

This is the fork of https://github.com/nuwber/rabbitevents

The goal was to enable of multiple bindings support in listeners. The original listener is only capable of handling a single event type or all of them (wildcard '*')
Sometimes you do not want to make a listener for every event, but listening to anything is also not an option, cutting you from events prioritisation.

Now listeners accept a comma-separated list of event names to listen to! 