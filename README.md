# Real-Time Intruder Notifier(Camera Feed)

## Under Construction. Patience is the key!!


## Future Improvements:
- [ ] Reduce Inference latency

 Currently, the function calls have the following time delays:

|After Fn call       | Frames processed/~10sec|
|    :---:           |        :---:           |
|model.predict       |          72            |
|Decode_netout:      |          17            |
|rescale_yolo_boxes: |          15            |
|do_nms:             |          03            |
|filter boxes:       |          02            |
|        -           |           -            |
|final:              |          02            |
