# second_challenge_toshiki

## System
<p align="center">
  <img src="https://user-images.githubusercontent.com/82020865/186935476-fbb8fae4-c243-412c-a0be-0c5dd2163d71.png" width="640px"/>
</p>

## Nodes
| Node | Method |
| ------ | ------|
| localizer | emcl: mcl with expansion resetting |
| global_path_planner | A* search algorithm |
| local_map_creator | Ray casting update |
| local_path_planner | DWA: Dynamic Window Approach |
