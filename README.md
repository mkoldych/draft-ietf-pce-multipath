# pce-mp

PCEP Extensions for Signaling Multipath Information 

Current PCEP standards allow only one intended and/or actual path to
be present in a PCEP report or update. Applications that require
multipath support such as SR Policy require an extension to allow
signaling multiple intended and/or actual paths within a single PCEP
message. This document introduces such an extension. Encoding of
multiple intended and/or actual paths is done by encoding multiple
Explicit Route Objects (EROs) and/or multiple Record Route Objects
(RROs). A special separator object is defined in this document, to
facilitate this. This mechanism is applicable to SR-TE and RSVP-TE
and is dataplane agnostic.

