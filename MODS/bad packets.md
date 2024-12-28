Bad Packets is a library that allows packet messaging between different modding platforms.

This means a Fabric client version of a mod that uses Bad Packets can send a packet to a server that uses the Forge version and vice versa.

This mod **DOES NOT** magically make all mods that have versions for different platforms to be compatible with each other, the developer needs to use BP's API to send its packet. Even then there are more complicated things like game object id sync that this mod doesn't handle which makes it unrealistic to support in the first place.
https://www.curseforge.com/projects/615134