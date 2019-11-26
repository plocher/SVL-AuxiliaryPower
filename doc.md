Silicon Valley Lines' model railroad layout uses a dedicated power
bus for all layout animations (street lighting, building lights,
signs, sound modules...) This board is the interface between that
high power bus and local (per module or per area) low power needs.

For layout animation and lighting, think "simple 555 based circuits",
flashing emergency vehicle lights, streetlights, "arduinos" and
"grain of wheat/rice bulbs".  These circuits need:

  * 12v for motors/animation
  * 9v for lights (derated from 12 to make them last longer)
  * 5v for "logic" circuits
  * 1.5v for structure lights
  * DCC for accessory decoders

This device can interface to the DCC Accssory bus or a dedicated 12VDC bus and provides:

  * 2x user adjustable switching supply outputs (1.3v - 30v @ 1A),
  * a rectified/filtered 12-14vDC and
  * A 1A fused DCC feed

The regulation is done by Buck Step-down LM2596 Power Converter Module DC 4.0~40 1.3-37V with LED voltage feedback
See http://www.ebay.com/itm/222245521575

