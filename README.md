# Real-Time Intruder Notifier(Camera Feed)

## Under Construction. Patience is the key!!


## Future Improvements:
- [ ] Reduce Inference latency

 Currently, the function calls have the following time delays:

|After Fn call       | Frames processed/10sec|
|--------------------|---------------|
|yhat:               |72frames(10.9s)|
|Decode_netout:      |17frames(10.6s)|
|rescale_yolo_boxes: |15frames(10.5s)|
|do_nms:             |03frames(11.9s)|
|filter boxes:       |02frames(11.6s)|
|        -           |         -     |
|final:              |02frames(11.4s)|
