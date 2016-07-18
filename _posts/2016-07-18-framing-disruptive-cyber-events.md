---
description: "While all disruptive cyber events aim to affect an organization’s ability to produce, deliver, or communicate with its target audience, a malicious actor may utilize multiple tactics that have wildly different disruptive outcomes. These events might include the deletion of data across a wide range of corporate networks, the destruction of physical equipment used to produce goods, an attempt to prevent users from reaching a website, or the denial of access to a social media account. Given the wide range of disruptive events it is useful to\_categorize events by using both the tactics employed by the attacker and by measuring the impact of the event itself. To measure the impact of the disruptive event we might consider: where the event occurs in a network topology, the magnitude of the effect, and the length of time the disruption affects the organization’s operations. There are three framing questions that must be answered for any given disruptive event. These include:"
dateModified: '2016-07-18T10:17:28.211Z'
datePublished: '2016-07-18T10:17:43.265Z'
title: Framing Disruptive Cyber Events
author: []
starred: false
sourcePath: _posts/2016-07-18-framing-disruptive-cyber-events.md
inFeed: true
hasPage: false
inNav: false
_type: MediaObject

---
# Framing Disruptive Cyber Events

While all [disruptive cyber events][0] aim to affect an organization's ability to produce, deliver, or communicate with its target audience, a malicious actor may utilize multiple tactics that have wildly different disruptive outcomes. These events might include the deletion of data across a wide range of corporate networks, the destruction of physical equipment used to produce goods, an attempt to prevent users from reaching a website, or the denial of access to a social media account. Given the wide range of disruptive events it is useful to [categorize events by using both the tactics employed by the attacker and by measuring the impact of the event itself][1]. To measure the impact of the disruptive event we might consider: where the event occurs in a network topology, the magnitude of the effect, and the length of time the disruption affects the organization's operations. There are three framing questions that must be answered for any given disruptive event. These include:

 What is the scope of the disruption?

 What is the magnitude of the disruption?

 What is the duration of the disruption?

The scope of a disruptive event is a function of a computer network's topology, the number of computers or equipment affected, and the importance of those computers to the overall network. While shear numbers of impacted computer systems are one factor contributing to the scope of the action, the importance of a specific system in that network may matter more than thousands of other devices. For example, corporations that use virtualization technologies to quickly scale and efficiently maintain their networks may find that their inability to use the high-end servers that provide virtual machine images to their employees has broader implications than taking 100 client machines offline.

The magnitude of a disruptive event is tied to the impact a malicious actor has on the key underlying services that support an organization's key production functions. If an organization's production of goods or services is tied to the deployment of labor, capital, and technology, then interruption of technology that enables the interaction of labor and capital is the key determinant of the magnitude of the event. The range of disruptive magnitude therefore is directly tied to the productive capacity of the underlying computer systems. For example, a computer used by employees to send emails and other correspondence may not be as productive as the device that controls automated assembly in a manufacturing plant. So while both devices have some productive value to the enterprise, the ability to differentiate the magnitude of impact is a key factor in our analysis.

The duration of an event is the third dimension of our analysis. Along with the scope and magnitude of a disruptive event, understanding the duration of an event along with the spillover effects it may have on an organization's operations is critical to differentiating between event types. The use of a botnet to launch a DDOS-type attack against a firm's webserver is likely to last from minutes to perhaps a day. That event differs significantly from a situation in which a malicious actor is able to modify a control system in a manufacturing plant, potentially destroying physical capital and causing production slowdowns for months.

It is possible in theory to specify a mathematical model that synthesizes these three dimensions into a single measure of cyber disruption. We can define the scope of the event by summing across all the nodes in a network and multiplying by importance (centrality). The magnitude of the event is the defined as, for each node, the ratio of the disruptive effect on a node to its productive capacity. This enables us to estimate the portion of production for each node that is "disabled" due to a disruptive cyber event. Finally, the product of the scope and magnitude is summed over time to account for the duration of the disruptive event.

The score, or Cyber Disruption Index (CDI), represents a single value that accounts for the three dimensions of analysis. That value can be used as a means of ranking events, thereby establishing a means of comparative analysis. 

[0]: https://www.linkedin.com/pulse/cyber-attack-generic-terms-understandable-confusion-harry-phd?trk=prof-post
[1]: http://www.cissm.umd.edu/sites/default/files/CategorizingDisruptiveCyberActivity%20-%20080615.pdf