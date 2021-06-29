# Real-Time Intruder Notifier(BETA)

## Under Construction. 
#### Patience is the key!! Meanwhile take a pair of dumbbells and take a view of [Biceps Curl Counter](https://github.com/niteshctrl/BicepCurlCounter)

---

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
