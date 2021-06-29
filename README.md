# Real-Time Intruder Notifier(BETA)

## Under Construction. 
#### Patience is the key!! Meanwhile grab a pair of dumbbells and have a look at [Biceps Curl Counter](https://github.com/niteshctrl/BicepCurlCounter)

---

## Improvements TBD:
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
