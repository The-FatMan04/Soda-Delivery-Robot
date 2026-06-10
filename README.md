# Soda Delivery Bot

### Project Details
* **Authors:** Andrew Adams
---

## Objectives

### Main Objective
* For this project, students need to build a robot from REV pieces capable of driving and include a mechanism to offer recipients beverages.

### Secondary Objectives
* The mechanism needs to be attached to the robot and be able to dispense the beverage to customers.
* The robot should be able to safely transport a beverage to a customer and use a mechanism in order to offer the beverage to the customer.

---

## Introduction
The rise of autonomous delivery robots in environments like college campuses has redefined modern logistics, requiring a mobile robot that can navigate complex human environments while securing fragile payloads. This project is analogous to those real-world systems, as it requires the engineering of a stable chassis capable of maneuvering through the school building to deliver a beverage to a specific target. For this project to be considered successful, the robot must traverse the designated route and safely execute a handoff where it presents a canned drink without wobbling or dropping the item.

---

## Fabrication Method and Procedure

### Part 1: Research and Design
When designing the delivery mechanism for the robot, my primary goal was to create an enclosed vertical indexing system that could safely contain and lift three standard soda cans without any risk of tipping during transport. Using the open space available in the center of our 6-wheel tank drive chassis, we designed a vertical "magazine" style cage out of four parallel REV 15mm extrusions to act as corner pillars. We set the internal dimensions of this enclosure to provide just enough clearance for a standard soda can to slide smoothly without shifting or tilting.

To lift this payload out of the enclosure, we integrated the REV Linear Motion Kit directly behind the cage, using brackets to mount the dual slide towers rigidly to the chassis at a strict 90-degree angle. A custom plate was then attached to the moving carriage of the slides, extending through a gap in the back of the enclosure to sit directly beneath the soda can. Powered by a REV HD Hex Motor mounted at the base to keep the center of gravity low, this continuous pulley-and-string system was designed to uniformly lift the platform, indexing the entire stack upward to present the sodas sequentially at the top of the cage one by one.

#### Milestones
* **Milestone 1:** Assemble the 6-wheel tank drive chassis and its internal cross-bracing. This provided a rigid structural base and a secure mounting area for the REV Control Hub and battery, ensuring the robot was fully mobile and counterbalanced before adding the delivery mechanism.
* **Milestone 2:** Assemble the dual vertical towers from the REV Linear Motion Kit. This milestone was achieved when the sliders were properly aligned, and the high-strength orange nylon rigging string was successfully routed through the integrated pulleys without binding.
* **Milestone 3:** Constructed the vertical magazine-style enclosure, using four parallel REV 15mm extrusions to create the payload space.

### Part 2: Building Procedure
The first step in building was to create a mounting area for the delivery mechanism and electronics. We installed two internal cross-braces using U-channels, which created a "deck" in the center of the robot. We then mounted the REV Control Hub and the 12V Slim Battery to a building plate at the rear of the robot. This placement was intentional, as it acted as a counterweight to prevent the robot from tipping forward once the sodas were loaded into the front (**Figure 1**).

Once the chassis was stable, we moved on to the delivery system. Using the REV Linear Motion Kit, we assembled two vertical slide towers (**Figure 2**). We then attached these towers vertically to the front cross-braces of the chassis using 90-degree angle brackets to ensure they stayed perfectly upright during extension.

To hold the sodas, we constructed a "magazine" cage around the towers using four vertical extrusions spaced evenly apart with C-channels in between each to act as walls (**Figure 3**). Finally, we attached a motor at the bottom, keeping it in place through pillow brackets. We then threaded the string through the gears along the motor so when the motor spun, it would wind the string, thus pulling the platform up.

#### Engineering Challenges & Testing Iterations
With the main stages of construction done, we moved on to testing to see what worked and what needed improvement. Quickly, we noticed two key problems:
1. The carrying bay was not secure enough, which would let the delivery fall out.
2. The slide towers were not secure enough, which allowed them to wobble around while driving.

These were both problems that negatively impacted the efficiency of my robot and needed to be solved.

* **Carrying Bay Solution:** To ensure the carrying bay was secure, we attached a back panel made out of plastic so the soda wouldn't fall out behind, and tied surgical tubing through the front to ensure the soda wouldn't fall out that way, while also not inhibiting the ability to grab the sodas out upon delivery.
* **Tower Slippage Solution:** To solve the tower slippage, we attached two pieces of extrusion mounted together to the base of the robot to ensure the towers would not move around (**Figure 4**).

---

## Observations, Data, Findings, and Results

### Part 1: Data Presentation

| Recipient | Success? | Notes |
| :--- | :--- | :--- |
| Dr. Dunleavy | Yes | Received with enthusiasm |
| Mr. Fabrizio | Yes | No |
| Dr. Zagarella | Yes | No |
| Fr. Orlando | Yes | No |
| Mrs. Tantilo | Yes | No |
| Dr. Swope | Yes | No |
| Mrs. Grahn | Yes | No |
| Mrs. Baracco | Yes | No (Trial 1) |
| Mrs. Baracco | Yes | No (Trial 2) |
| Mrs. Frank | Yes | No |
| Mrs. Stephan | Yes | No |
| Mr. Radomile | Yes | Extrusions started to lose their lubrication, which led to the platform not lowering as easily |
| Mrs. Johnson | Yes | Same as Mr. Rad |
| Mr. Roxberry | Yes | Same as Mr. Rad |
| Mr. Shimpino | Yes | Same as Mr. Rad |
| Mrs. Buzbee | Yes | Same as Mr. Rad |
| Mr. Einstman | Yes | Same as Mr. Rad |
| Mrs. Si | Yes | Same as Mr. Rad. The middle schoolers started swarming the robot, trying to steal the sodas. |

---

## Conclusion
The task was completed without any major flaws. The robot could improve with a more secure plastic platform as the base, and potentially more room for a second beverage. The higher quality platform would make for a more stable base for the beverages, and lead to the beverages moving less. The increased size would allow for a second beverage to be held, allowing for multiple deliveries with one resupply. It could also allow for options for customers to choose from if they are unsure of what they desire.

The platform could be achieved by using screws to secure the base and place a final corner bracket under the top left side of the platform. The increased size could be accomplished with changes to the design of the arms to make them more spread apart, but would need more support in the middle.

The design for the robot was the best possible design for the task at hand, and if given another chance for the project, would create a similar design to the current one. It has safety precautions in order for the beverage not to be damaged or altered with the surgical tubing, a sturdy foundation and driving mechanism with the standard drive train, and a slow method of delivery ensuring no damage to the beverage or machine in the process.
