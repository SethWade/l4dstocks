#### Syntax: ####
```
   stock bool:L4D2_CreateInstructorHint(const String:name[], 
                                        target = 0, 
                                        const String:caption[], 
                                        color[3] = {255, 255, 255}, 
                                        const String:iconOnScreen[] = "icon_tip", 
                                        const String:iconOffScreen[] = "icon_tip", 
                                        const String:binding[] = "", 
                                        Float:iconOffset = 0.0, 
                                        Float:range = 0.0, 
                                        timeout = 0, 
                                        bool:allowNoDrawTarget = true, 
                                        bool:noOffScreen = false, 
                                        bool:forceCaption = false, 
                                        flags = L4D2_IHFLAG_STATIC);
```

#### Usage: ####
```
   name                      Instructor hint name.
   target                    Entity index of target.
   caption                   Caption of hint.
   color                     Color of the caption. RGB format.
   iconOnScreen              Icon when hint is on screen.
   iconOffScreen             Icon when hint is off screen.
   binding                   Key binding to show.
   iconOffset                Height offset for icon from target entitys origin.
   range                     Display range of hint. 0 for unlimited range.
   timeout                   Timeout out for hint. 0 will persist until stopped with L4D2_EndInstructorHint.
   allowNoDrawTarget         Whether hint will work with targets that have nodraw set.
   noOffScreen               Whether when hint is off screen it will show an arrow pointing to target.
   forceCaption              Whether the hint and icon will show even when occluded a wall.
   flags                     Hint flags.
```

#### Notes: ####

> Both survivor and infected players will see this type of hints.

> Hint is not visible to the player if dead.

> No more than 1 hint at a time can be displayed.

> If player were not present at hint creation, they will not be able to see the hint.

> Hint does not support multi-byte characters.

> See [Instructor Hint Icons](InstructorHintIcons.md) for a list over available icons.

> See instructor hint bit flags for valid flags.

#### Return: ####
> True if created, false otherwise.

#### Version Added: ####
> r4669c8dac585