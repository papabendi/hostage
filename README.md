# Take Hostage
Modified very slightly for QB, can also be implemented into the qb-radialmenu with a snippet like below. I personally just re-named the previous event.

Copy and paste, ensure in your server.cfg and good to go

I do not take credit for the code, only the very minor changes which took all of a couple of minutes.
This version also uses cd_drawtextui, but you can just remove that code and uncomment the original on screen text if required.

Can also be triggered with /th


```lua
                   {
                        id = 'escort554',
                        title = 'Hostage',
                        icon = 'child',
                        type = 'client',
                        event = 'TakeHostage:client:hostage',
                        shouldClose = true
                    }
```

Credit for original resource:
https://github.com/rubbertoe98/FiveM-Scripts/TakeHostage/

Original Readme:
# Take Hostage by Robbster

Instructions on how to use:
Type /takehostage, a valid weapon is needed(Add or remove weapons in cl_takehostage.lua)
Then press G to release the hostage or H to kill the hostage!

Feel free to make improvements with PRs
