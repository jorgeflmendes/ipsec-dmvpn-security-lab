# Architecture Notes - IPSec and DMVPN Security Lab

## Lab Topology

The IPSec topology connects two private sites across a public transit network using Cisco routers. The DMVPN topology uses one hub and two spokes over a public underlay, with NHRP enabling direct spoke-to-spoke forwarding after initial redirection.

## Evidence Flow

The repository keeps the final report text and selected screenshot figures. Raw captures and appliance images are excluded.

## Publication Boundary

The repository keeps report source and selected reviewed evidence. It deliberately excludes:

- Cisco/GNS3 appliance images
- raw Wireshark captures
- private course PDFs
- local debug logs
- GNS3 project IDs

## Reproduction Assumptions

The lab was executed in GNS3 using Cisco/GNS3 appliances and Linux containers. Re-running the full topology requires local access to those appliances and the original lab guide.
