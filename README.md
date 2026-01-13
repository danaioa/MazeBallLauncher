# Maze Ball Game with Catapult and Ultrasonic Sensor

## General Description
This is an interactive robotics project: a ball moves through a **cardboard maze controlled by a joystick**, and at the end, it reaches a **catapult**.  

When the ball is detected on the catapult using an **ultrasonic sensor**:
- A green LED lights up
- A point is added to the score
- A buzzer plays a background melody  

If the ball is no longer present on the catapult:
- The green LED turns off
- A red LED turns on  

The catapult servo launches the ball back to the start, allowing the game to be repeated.

---

## Bill of Materials (BOM)

| Component                     | Quantity |
|-------------------------------|----------|
| Arduino (Uno or Nano)         | 1        |
| Catapult servo motor           | 1        |
| Analog joystick                | 1        |
| Ultrasonic sensor (HC-SR04)   | 1        |
| Green LED                      | 1        |
| Red LED                        | 1        |
| Piezo buzzer                   | 1        |
| Ball                           | 1        |
| Cardboard                      | as needed |
| Wires and resistors            | as needed |

---

## Source
The project is inspired by classic concepts of:
- Mechanical maze games
- Servo control with joystick
- Detection using an ultrasonic sensor

### Additions
- Catapult at the end
- LEDs and visual feedback
- Background music using a buzzer
- Scoring system based on ball detection with ultrasonic sensor

---

## Instructions for Use
1. Connect the Arduino, catapult servo, LEDs, buzzer, and ultrasonic sensor according to the schematics.  
2. Place the ball at the start of the maze.  
3. Move the joystick to guide the ball through the maze.  
4. When the ball reaches the catapult:  
   - The ultrasonic sensor detects the ball -> green LED ON and score increases  
   - The catapult servo launches the ball back to the start  
5. If the ball is no longer detected -> red LED ON

