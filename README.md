# fornutig-air-purifier

esphome code and instructions to modify the fornutig ikea air purifier.

The beauty of this approach is that it's 100% transparant, any cahnge that you make on the device will be reported in home assistant and home assistant is able to override it at any time so if your grandma comes over and just want to turn it on yet hasn't touched a computer in her life, your automations won't break.

card.yaml is code for a card to operate it, not essential but could be usefull. Requires card-mod to work but you can easily just remove that part if you want and be done.

# Step 1

Looking at the board with the text reading right (same for every steps) cut the four bottom pins and bend the remaining part up so that you can solder wires to them as marked in the picture bellow.

![PXL_20241205_164308322 MP~2](https://github.com/user-attachments/assets/4f403741-13f4-4192-b5bd-4f9692cfdf66)

# Step 2

On the other side of the board, heat up the pins that were cut and remove the remaining part. Solder wires to the pads as marked in the following photo.

![PXL_20241205_164333997~2](https://github.com/user-attachments/assets/f47bfffe-7c73-4633-a8dc-c9868fe0eac0)

# Step 3

Tap in the 24v and GND toward a step-down converter to get the 5v to power the wemos D1 mini. Also, add a wire to the led as marked in the following picture (be careful, it's between R9 and the led pin).

![PXL_20241205_164323333~2](https://github.com/user-attachments/assets/20a90854-b66f-494c-bfd2-bf7988047ec6)
