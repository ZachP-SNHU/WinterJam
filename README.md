# Time Warp Gameplay Mechanic C++ Version[^1]
[^1]: This is a part of a templated game jam

## Controls Default:
- **Left Mouse: Shoot a sphere trace that freezes an object in time**
- **Right Mouse: Unfreezes all objects**
- **Scroll Wheel Down: Begins reversing time on *ALL* frozen objects. Incrementally increasing reversing speed the more you scroll.**
- **Scroll Wheel Up: Slows down and eventually freezes all reversing objects in time.**

## Info:
The mechanic in its current form functions using a combination of a custom time warp component and time warp interface on an object.
This method was used as it allows for the mechanics functionality to be changed and altered more easily. Ie for a character to be affected appropriately
the component's functionality may need to be expanded and the implementation of the interface on the character would need to be adjusted accordingly.
