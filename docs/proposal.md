---
layout: default
title:  Proposal
---

## Summary of the Project (30 points)
The aim of our project is to participate in the Collaborative AI Challenge. We will implement and train an agent that can collaborate with any collaborator to try to capture the pig in the "Pig Chase" challenge.

#### Overview of the game:
Two Minecraft agents and a pig are wandering a small meadow. The agents have two choices:
  * Catch the pig (i.e., the agents pinch or corner the pig, and no escape path is available), and receive a high reward (25 points)
  * Give up and leave the pig pen through the exits to the left and right of the pen, marked by blue squares, and receive a small reward (5 points)

#### How to play
  * The game is played over 10 rounds at a time. Goal is to accumulate the highest score over these 10 rounds.
  * In each round a "collaborator" agent is selected to play with you. Different collaborators may have different behaviors.
  * Once the game has started, use the left/right arrow keys to turn, and the forward/backward keys to move. You can see your agent move in the first person view, and shown as a red arrow in the top-down rendering on the left.
  * You and your collaborator move in turns and try to catch the pig (25 points if caught). You can give up on catching the pig in the current round by moving to the blue "exit squares" (5 points). You have a maximum of 25 steps available, and will get -1 point for each step taken.

## AI/ML Algorithms (10 points)
In a single sentence, mention the AI and ML algorithm(s) you anticipate using for your project.  It does not
have to be a detailed description of the algorithm, even the sub-area of the field is sufficient. Examples of this
include “planning with dynamic programming”, “reinforcement learning with neural function approximator”,
“deep learning for images”, “min-max tree search with pruning”, and so on.

## Evaluation Plan (30 points)
As described in class, mention how you will evaluate the success of your project. In a paragraph, focus on the
quantitative evaluation: what are the metrics, what are the baselines, how much you expect your approach to
improve the metric by, what data will you evaluate on, etc. In another paragraph, describe what qualitative analysis
you will show to verify the project works, such as what are the sanity cases for the approach, how will you visualize
the internals of the algorithm to verify it works, what’s your moonshot case, i.e. it’ll be awesome and impressive if
you get there. Note that these are not promises, we’re not going to hold you to what you say here, but we want to
see if you are able to think about evaluation of your project in a critical manner.

## Appointment with the Instructor (15 points)
One member of the group should take an appointment with the instructor in the week starting 4/23 (or 4/30, if
no slots are available). Select a time such that all members of the group can attend, unless one or more members
of your group can absolutely not make any of the available times. In the proposal page, mention the date and time
you have reserved the appointment for.