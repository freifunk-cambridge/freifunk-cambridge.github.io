# Get involved

We're currently in the exploratory stage of building a Freifunk-style internet sharing community in Cambridge and surrounding areas. 

The core aims of this would be to:

  - Build an open, free to all network using wireless mesh technology. This would help to move away from dependence on large, commercial internet providers. This would mean many services hosted in the area could continue to be available in an internet outage scenario.
  - Develop customised versions of Freifunk firmware (based on OpenWRT and Gluon) that users can flash to existing routers to make them part of the network.
  - Build a redundant network with multiple exit points contributed by users. This will ensure efficient routing of traffic destined for the wider internet, and make the network resilient to a single Internet provider outage.

For the first stages of the network, we're exploring the possibility of tunnelling traffic to an out-of-region, central gateway. This would greatly simplify the operation at this early stage, and would mitigate any risks of the activity of users being linked to the connections of node operators.

Our planned next steps are:
  - Explore the possibilities for where this external gateway could be hosted. We have so far established this will need 1 public IPv4 address, and a minimum of a /64 of IPv6 address space (preferably a /56).
  - Configure the gateway with an initial testing network.
  - Create our first customised version of the Gluon firmware (with minimal changes at this stage). We plan to use WireGuard for the VPN connections back from participant nodes, and BATMAN as the routing algorithm.
  - Host a couple of test routers ourselves, and invite other users to join in at this early stage of network development.


We're currently at the stage where any expressions of interest would very much be welcome, whether from potential participants or help/advice from existing Freifunk communities. 

You can contact the team at [cambridge-owner@freifunk.net](mailto:cambridge-owner@freifunk.net)