cant guarantee integration tolerances will be great. I usually integrate to 1e-12 but sometimes it's worse. But also sometimes it's better, so you never know what you're gonna get. It's like a box of chocolates that way.

Unless specified otherwise, mu=1.215058560962404e-2 (stolen from JPL a while ago).

Numenclature subject to change, but for now it's (body or Lagrange point)(number) (Family Name) (bifurcation type, P=period-multiplying) (notes). For instance:

P2 DPO P3a (spatial) would mean
- P2-centric
- Bifurcates from distant prograde orbit family
- period-tripled, the first (implied of multiple)
- spatial orbit

When a bifurcation is not symmetric with respect to + or - tangent vector, negative indices denote one direction while positive denote the other direction. If the resulting families are symmetric (i.e. southern vs northern halos) or the same (i.e. many period doublers of planar orbits) then the negatives are omitted

Relies on https://github.com/northstar-code/dynamicslib

NOTE: There may be (probably is) some repeats between families, i.e. L4 Short Period P4 and L4 Long Period

TODO: I will make a subway map of what connects to what (i.e. where the period multipliers start, the short period -> L3 Lyapunov connection, L4 axial -> L1 NRHO connection, etc)