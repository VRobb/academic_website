---
date: "2021-01-01"
math: true
title: Longitudinal Studies Tracking Individual Users as They Gained Experience
type: book
weight: 40
---
We conducted two longitudinal experiments in the final phase of this project. In both experiments, users without prior VR experience were recruited to participant in a multi-week experiment. Participants were loaned an Oculus Quest HMD for the duration of the experiment and were allowed to use it for whatever they wanted to. Participants were also asked to complete custom activities we created on a regular basis. Each experiment included multiple different activities due to the complexities associated with recruiting and running a longitudinal experiment.

Each experiment included three activities. The Rotational Gain and Proprioceptive Offset activities were included in both experiments, the Locomotion and Navigation activity was included in the first experiment, and the Depth Perception activity was included in the second experiment. In both experiments, participants were presented with a schedule upon loading our custom application. This enforced the order and rate at which participants could complete the assigned activities.

### Sensitivity to Rotational Gain
A motion in real life does not have to be faithfully reproduced in VR. When a user turns their physical head 90&deg;, the software rendering the VR environment could show this as a 135&deg; rotation. In this case, a gain of 1.5 has been applied to the rotation. If the gain is small enough, it may not be noticed by the user. Rotational gains are used by *redirected walking techniques* to allow users to physically walk in virtual spaces that are larger than the physically available space. As users walk towards the boundary of the space, a small rotational gain is applied to curve the user back towards the center of the physical space while they appear to be walking straight in VR.

This experiment sought to understand how sensitivity to rotational gain changed over time as users gained more experience with VR. Participants were presented with a series of trials where they were asked to turn their head in one direction and then in the other. A gain was applied to one of these rotations. After turning in both directions, users were asked which rotation had had the gain factor applied. Participants' responses to these trials were used to construct a psychometric model that reported the percent likelihood of correctly detecting whether a gain was present for a gain of a given magnitude.

The results of this activity suggested that participants became more sensitive to rotational gain as time progressed. When starting the experiment, participants could detect gains smaller than 0.803 and greater than 1.242; by the end of the experiment, participants could detect gains smaller than 0.894 and greater than 1.095. As large rotation gains can cause people to experience VR sickness, we also explored how sickness changed over the course of the experiment, however, no effect was observed here.


### Sensitivity to Proprioceptive Offsets
Similarly, your virtual hands do not need to be shown in the same position as your real hands. This is referred to as a proprioceptive offset. Proprioceptive offsets can occur naturally due to tracking inaccuracies, or can be created deliberately to expand what a user is capable of. For instance, the go-go interaction technique pioneered by Ivan Poupyrev et. al[^go-go] allows users to grab objects outside of normal arm reach by applying a gain to the hand's position once it gets a certain distance away from the body.

This experiment sought to understand how sensitivity to proprioceptive offsets changed over time as users gained more experience with VR. Participants were presented with a series of trials where they were asked to stack two sets of blocks, presented sequentially. A proprioceptive offset was applied to one of the stacking tasks. After stacking both sets of blocks, users were asked which stack had had the proprioceptive offset applied. Participants' responses to these trials were used to construct a psychometric model that reported the percent likelihood of correctly detecting whether an offset was present for a offset of a given magnitude.

Unlike sensitivity to rotation gain, participants did not appear to grow more sensitive to proprioceptive offsets as they gained more experience. However, participants' hands were more likely to stay in their peripheral vision as they gained experience, which may indicate that participants become more comfortable performing tasks when a proprioceptive offset was present.

### Locomotion and Navigation
In the “navigation” activity, participants used either teleportation orjoystick locomotion to explore twenty maze-like levels (see Figure 2c).In order to reach the end of the level, they had to first find a keycardlocated in one of the rooms. After finding the keycard, they could useit to open a locked door leading to the exit. Once arriving at the exit,participants were asked to point back in the direction of where they hadstarted and where they had found the keycard.  They also completeda presence and a simulator sickness questionnaire in between levels.Prior to beginning the experiment, participants were randomly assignedto one of the locomotion conditions, which they then used in each ofthe sessions


### Depth Perception
We are constantly judging distances whenever we interact with our environment. Prior research has consistently found that distances are underestimated in virtual reality, although the reason for this is not yet settled. However, depth perception can be calibrated through repeated action and feedback which occurs when users interact with virtual environments. 

This experiment focused on whether depth perception improves or changes as users gain experience with VR, including a particular emphasis on the process of calibration. Participants were asked to use a thin rod to reach out and touch objects placed at different distances from them. Every reach was a blind reach, where the participants' vision was obscured while actually reaching, forcing them to rely on their judgment of the distance of the object when they began to reach. Participants sometimes received feedback about if they had reached the target successfully and other times did not. As calibration is heavily influenced by feedback, this allowed us to explore the effect of calibration separate from participants' baseline performance.

#### Publications from this phase of the project

- [ \[Pre-print\] Andrew Robb, John Porter, Kristopher Kohm. Experience Matters: Longitudinal Changes in Sensitivity to Rotational Gains in Virtual Reality]({{< relref "/publication/porter-2019-analysis" >}})

- [\[Pre-print\] Kristopher Kohm, John Porter, Andrew Robb. Proprioceptive Offset Detection Thresholds: A Longitudinal Study]({{< relref "/publication/porter-2019-analysis" >}})

- [\[Pre-print\] Moloud Nasiri, Kristopher Kohm, John Porter, Andrew Robb. Navigation and Locomotion over time]({{< relref "/publication/porter-2019-analysis" >}})

- [\[Pre-print\] Kristopher Kohm, John Porter, Sabarish Babu, Andrew Robb. Depth-perception over time]({{< relref "/publication/porter-2019-analysis" >}})


[^go-go]: Poupyrev, Ivan, et al. "The go-go interaction technique: non-linear mapping for direct manipulation in VR." Proceedings of the 9th annual ACM symposium on User interface software and technology. 1996.