Standardized base frame
===

Used by all <a href="http://github.com/worlddevelopment">worlddevelopment</a> mobile machines.



Functions | capabilities
---

Mechanics:
<a href="capabilities.xml">capabilities.xml</a>

Electricity:
* illuminate (a capability of the lights, any of its attachments are checked for this action and if the item can be used/operated)
* alternative power source to OSE combustion hydraulic power cube



Requirements
---
Mechanics:
* modular
* rigid
* stackable
* square
* battery holder

Electricity:
* repairable
* rigid, simple connectors
* scalable



Technologies
---
''TODO: Outsource into JSON file to allow reuse in the <a href="http://github.com/worlddevelopment/virtual_time_machine">Virtual Time Machine</a>.''
* Electricity (battery recharge interface, electrical cooperation)
* Mechanics (frame, coupling, ...)



Dependencies
---
(none, base module)



Related modules
---
see <a href="http://wiki.opensourceecology.de/0install">0install</a>

* `link_coupling` (universal) maybe tailored for the frame, id est `frame__link_coupling`
* `frame_leg`
* `frame_track`
* `frame_wheel`

where e.g.
* `frame_track` | `frame__track` is a module that tailors a track to fit the frame.



Reverse dependency examples
---
* `walker` | `legged_frame` (universal, high traction, high stability, climbing angle skill magnitude of 45°) horizontal version, id est more than two legs
* `wheeler` | `wheeled_frame` (high speed mobile frame)
* `roller` (high traction, high pressure distribution, medium speed)

where e.g.
* `legged_frame` is a module that combines [frame_]legs, mobile frame resulting in a mobile base.



Links
---
* Manual (not available)

