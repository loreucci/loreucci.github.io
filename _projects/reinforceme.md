---
layout: page
title: ReinforceMe!
description: Reinforcement learning in Unreal Engine
headertitle: ReinforceMe!
img: assets/img/ReinforceMe.png
importance: 1
category: games
---

The idea of this project came to me while studying the classic *Reinforcement Learning: An Introduction* by Sutton and Barto. The goal was to create a simple, interactive, reinforcement learning scenario inside Unreal Engine 4. For now, the core with the learning algorithm has been implemented, but the work on the interaction is still ongoing.

The work is still ongoing, but the core has been impl: an agent starts from the yellow tile and moves in a grid environment trying to reach a goal (green tile).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="/assets/img/ReinforceMe_FirstDemo_Start.gif" title="example image">
    </div>
</div>
<div class="caption">
    The agent exploring the environment with an epsilon-greedy policy. The arrows represent the preferred actions.
</div>

After a couple of minutes, thanks to *Q-learning*, the agent has discovered some short paths to the goal that also avoid the punishment (red tile).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="/assets/img/ReinforceMe_FirstDemo_End.gif" title="example image">
    </div>
</div>
<div class="caption">
    Behaviour of the agent at the end of the learning. There is stille exploration due to the epsilon-greedy policy.
</div>