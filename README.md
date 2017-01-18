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



Modules
---
see <a href="http://wiki.opensourceecology.de/0install">0install</a>

* `mobile_frame__legs` (universal, high traction, high stability) horizontal version, id est more than two legs
* `link_coupling` (universal) maybe tailored for the `mobile_frame`, id est `mobile_frame__link_coupling`
* `mobile_frame__tracks` (high traction, pressure distribution) extension tailoring chain tracks to the mobile frame
* `mobile_frame__wheels` (high speed) extension tailoring wheels to the mobile frame

Explanation: e.g. `mobile_frame__legs` is a module that combines legs, mobile frame resulting in a functional mobile base.
can be reused by machines.



Links
---
* Manual (not available)

