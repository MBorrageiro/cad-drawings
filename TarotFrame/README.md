# Tarot Frame
This folder is dedicated to components which were designed and intended for the Tarot 680 Pro Hexacopter frame however Solidworks file are available to edit for other frames.

## GPS Foldable Mast
This folder contains STL files for a foldable GPS mount. The original files were created in OpenSCAD and can be found [here](https://github.com/ndrk/folding_gps_mast).

The dimensions were edited to suit mouting on a Tarot frame.

**Files**:
- fmBaseTarot2Flanges.STL: 2 flanges 180&deg; apart on the mounting plate, holes 46mm apart.
- fmBaseTarot4Flanges.STL: 4 flanges 90&deg; apart on the mounting plate, holes 46mm apart.

## RFD Telemetry
3D printable attachment methods for the RFD900x Telemetry radio.

There are two designs to mount the RFD radios to the Tarot frame:
1. Housing which positions the radio inbetween the top and bottom plates towards the front side.
2. Clamped to the landing gear legs on a sensor mount.

### Design 1
This design clamps the RFD radio in place between the top and bottom frame plates with the antenna facing forward. The housing is secure by M2.5 nuts and bolts.

**Files**:
- RFDHousingTop.SLDPRT
- RFDHousingBot.SLDPRT

### Design 2
It is made up of a top and base designed to fit onto a sensor mount which is located on a 16mm rod. The case is secured to a sensor mount by a 2.5mm cable tie.

**Files**:
- RFDTopCoverV1.SLDPRT
- RFDBotCoverV1.SLDPRT
- RFDTopCoverV1.STL
- RFDBotCoverV1.STL

## RndArmClampV1
A 3D printable sensor mount. This is the first iteration and will be updated after evaluation.

The clamp is suitable to fitting on a 16mm rod, a fastening hole is provided for an M5 bolt with recommned length of 30mm however 25mm may suffice.

**Files**:
- RndArmClampV1.SLDPRT
- RndArmClampV1.STL