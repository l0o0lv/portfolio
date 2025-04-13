---
title: WheelchairTennisVR
summary: Mar. 2024 - Jun. 2024
date: 2024-10-01
type: docs
math: false
---

### Overview

'WheelchairTennisVR' is a VR application based on motion sickness theory.

- Documentation: [{{< icon name="hero/document" >}}](WheelchairTennisVR.pdf)
- Technologies Used: {{< icon name="devicon/csharp" >}} | {{< icon name="devicon/unity" >}}
- Dev. Environment: Meta Quest 2
- Dev. Period: Mar. 2024 - Jun. 2024

{{<youtube jTjOCecpAfE>}}

### <u>My Contributions</u>

#### Implementation
1. Wheelchair Movement
- Applied torque to the Wheel Collider for forward and backward movements.
- Used Transform Rotation for direction changes.
- Represented handrims with rectangular cubes on the sides of the wheelchair to reflect the actual hand movements of the rider during acceleration.
- Added sound and vibration to the wheels and handrims.

2. Tennis Related
- Determined racket and ball contact and differentiated weights for sweet spots and other areas.
- Implemented elasticity using Physical Material.
- Allowed players to gauge ball speed through ball trajectory colors.

3. Miscellaneous
- Provided realism with score determination and point light sources.

#### Motion Sickness Mitigation

4. Stabilization
- Implemented direction changes using Transform Rotation instead of torque to the Wheel Collider to prevent motion sickness caused by accelerated motion. Also fixed the Y-axis position.
- Added suspension to the Wheel Collider.
- Enhanced realism by appropriately adding sound and vibration and creating an indoor environment.

#### Usability Improvements

5. Physics Adjustments
- Adjusted the friction and stopping determination of the wheelchair to provide stable control.
- Interpolated the basic momentum of the ball and the racket’s momentum to maintain the core experience of "hitting the ball."
- Positioned the racket accurately to improve tracking accuracy.

### Limitations

1. Multi-play
- Need to implement functionality for multiple players to play the game.