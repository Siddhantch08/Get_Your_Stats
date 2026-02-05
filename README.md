# Get_Your_Stats
Football video analyser which takes our video with a specific quality metrics.

Lets start with Simple MVP:
Player Detection Model

- [ ] We need to create a Football video analyzer which takes our video with specific quality metrics.
- [ ] It should have a strong Tracking model that can easily detect a player, maybe with his/her jersey or some other kind of tracker.
- [ ] We can start with player movement tracking. If our analyzer can provide us with the player movement map, we are halfway there. 
- [ ] We need smart filtering that can be done w bounding boxes. (YOLOv8 + byte track).
 
YOLOv8(object detection model) and ByteTrack(multi-object tracker).  


Video frame
↓
YOLOv8 (bounding boxes)
↓
ByteTrack (consistent player IDs)
↓
Player trajectories. 


Phase 1 output :
- [ ] Avg. speed
- [ ] Distance covered
- [ ] Time
- [ ] Heat map

