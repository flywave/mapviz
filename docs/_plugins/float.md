---
name: "Float"
description: "Displays the most recent value from a `std_msgs::Float32/64, marti_common_msgs/Float32/64Stamped` or a `marti_sensor_msgs/Velocity` message at a fixed location on the scene."
image: ""
parameters:
  - name: "Topic"
    description: "The float topic"
  - name: "Font"
    description: "The font for rendering the float"
  - name: "Color"
    description: "The color for drawing the float"
  - name: "Anchor"
    description: "(top left | top center | top right | center left | center | center right | bottom left | bottom center | bottom right)"
  - name: "Offset X"
    description: "Horizontal offset from the anchor"
  - name: "Offset Y"
    description: "Vertical offset from the anchor"
  - name: "Units"
    description: "(pixels | percent of window)"
  - name: "Postfix"
    description: "Text to append to the displayed value (ex. to show units)"
---

# {{ page.plugin }}
