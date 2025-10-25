# XR Fusion Essentials
Some XR interaction toolkit features networked with Photon Fusion 2

## Documentation

Dependencies

https://github.com/HuhMonk/XRInputs for getting inputs from the xr controllers

### Assembly

```csharp
using XRFusion;
```

### Components

## NetworkedGrabInteractible

Properties

**Must be set manually** - XRGrabInteractable - The main XRGrabInteractible component.
```csharp
NetworkedGrabInteractible.interactible
```

bool - Returns if the interactible is cuurently selected.
```csharp
NetworkedGrabInteractible.isSelected
```

## Other info

Developed with XR Inteaction Toolkit version 3.0.8
Developed in unity version 6000.0.60f1
Developed using https://github.com/rxxyn/FlowVR
