6Lo Charter Discussion
======================

IETF discussion of a charter for 6Lo

Focus
-----

6Lo focuses on INT area work that is needed for constrained node networks,
as defined in section 2.1. and 2.2. of draft-ietf-lwig-terminology.
Specifically, it is working on

- IPv6-over-foo using 6lowpan (RFC4944) specifications for link layer technologies of
   interest in constrained node networks;
- related MIBs;
- common infrastructure specification such as header compression
   specific to constrained node networks;
- maintenance and informational documents required for the existing
   IETF specifications in this space.

Only specifications targeting constrained nodes and constrained networks, 
according to the definition in draft-ietf-lwig-terminology, are in scope.
6Lo will work closely with the 6man working group, which will continue
to work on IP-over-foo documents outside the constrained node network
space and will continue to be the focal point for IPv6 maintenance.
For adaptation layer specifications that do not have implications on
IPv6 architecture, 6man will be notified about 6Lo's working group
last call.
Specifications that might have such an impact (e.g., by using IPv6
addresses in a specific way or by introducing new ND options) will be
closely coordinated with 6man, and/or specific parts will be fanned
out to 6man documents.
Beyond 6man, 6Lo will also coordinate with LWIG and INTAREA.

6Lo works on small, focused pieces of INT area work.  6Lo does not
take on larger cross-layer efforts (such as the 6TSCH work under
discussion).  The working group will continue to reuse existing
protocols and mechanisms whenever reasonable and possible.

Security and management work that is not specific to the link layers
being worked on is out of scope.
Work related to routing is out of scope.
6Lo will coordinate closely with the working groups in other areas
that focus on constrained node networks, such as today ROLL (RTG) and
CoRE (APP), and appropriate groups in the IETF OPS and Security areas
including potential future groups spawned from efforts such as COMAN
and SOLACE.
