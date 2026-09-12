# Architecture

R1 and R2 use loopback addresses as IPsec tunnel endpoints over a routed public underlay. The configuration directory covers IKEv1/AH, IKEv1/RSA/ESP, and IKEv2/ESP.

DMVPN uses one mGRE/NHRP hub and two spokes. OSPF provides underlay reachability; RIP advertises the overlay networks. NHRP redirect on the hub and shortcut on the spokes enable direct spoke-to-spoke forwarding after the initial flow.
