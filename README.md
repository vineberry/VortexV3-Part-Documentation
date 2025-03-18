# VortexV3-Part-Documentation
Little repository focused on attempting to ID the different parts of the Vortex V3, a RAZR-clone flip phone with 2GB RAM and Android. Mainly so I can have a reference sheet (and maybe you, too!) when trying to track down individual parts. Honestly, this phone's amazing for the price. I just wish it had a better front display. Who knows? That and a better heat sink (it just has a thin thermal pad) would do wonders.

I'd 3D scan the shell components, but I don't have a way to do that.

If someone has a spare to safely decapitate the shielding on each side of the board, please let me know! Pictures of that and the unit would help a ton (for my own purposes, muahahaha).

I genuinely hope a modding scene comes out for this device. If all we'd have to do is transplant the main board (honestly, where most of the device cost comes from tbh) and salvage the ribbon cables, customization could just about be endless. We'd just have to make sure the pins line up properly.

# Visible silkscreens
The primary "hardware" components of the phone itself, including ribbon cables, have the primary identifier of `V39`. Individual components have variations of this.
Currently visible silkscreens include:

- `V39-MB-V1.0,` manufactured on `2023/10/31`. Components on the board are double-sided, though I do not have the ability to safely remove the shielding.
The motherboard does have a logo on it! It looks like an X, with three lines extending down from the bottom left side.
- `V39-MAINFPC-V1.1-20231113`, which connects the Motherboard to the main display unit. 
MB connector has markings `60 31` for the top row and `1 30` for the bottom. 
Display unit connector has markings `30 1` for the top row and `31 60` for the bottom, with `SUB` underneath.
- `V39-KEYFPC-V1.0`, dated as `2023-09-06` and additional markings `CYD-FD3.` Unsure if there are any additional under the direct T9 keyboard. 
Pin connector has markings of `13 12` for the top row and `24 1` for the bottom.
- 2MP camera has `C2599`, with `BCF-9900-0FD3-V2` underneath.
# Display Unit
I'm unsure if this would be from the same manufacturer, and I'm leaning towards it being an outsourced part. The unit itself is soldered to the speaker at the top, and the vibration motor at the bottom. For my own sanity, I disconnected the vibration motor. I don't really need it. You ARE likely to make noticeable cracks or dents if you open this part, as there are two screws near the camera that are physically threaded into the top shell. It sucks. I don't have a reason for it. The top cover of the camera SHOULD be removable, but I'm too afraid to break that specific part. Potato tomato.
The unit is double-sided, with each display seeming to be glued together.

Funnily enough, there does not seem to be any hardware-based signal converters on the unit itself. I could be missing it, but I truly believe it's on the motherboard which, in comparison, is incredibly easy to remove.

- The external display's ribbon cable has identifier `COi F14JN253-V1` on the ribbon cable, with a logo above.
- The internal display's ribbon cable has identifier `COi F24LS1133-K-V1` with additonal letters `AK` followed by `25-1`.

- The unit that combines the two displays has identifier `V39-SUB-V1.0`, dated `2023-09-15` and additional marker `CYD-FD3 2352`.
