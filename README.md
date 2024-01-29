# machine_learning_hw: Take-home ML project
## Objective
Build a model to predict forces experienced by Robots in the system.

## Context
At Machina Labs we use a Robotic Manufacturing System to form metal sheets into desired geometries. The manufacturing cell uses two opposing robots R1 and R2, applying pressure onto a metal sheet to deform it. The robots move along a path that allows the system to give shape to the metal sheet.

R1, the "Forming Robot" pushes into the sheet, in direction Z, while moving along a certain path in the X/Y plane, parallel to the sheet metal surface. The opposing "Support Robot" R2 pushes into the sheet from the other side, providing the "pinch". It too moves along a similar path but obviously not exactly the same as R1, in the X/Y plane.

Both robots experience forces at the tool-tip in X, Y and Z directions, and these forces are captured by sensors embedded into the robots. The force data is recorded along with position data from Robot encoders, as well as orientation data in form of Euler angles (Pitch, Yaw, Roll) A, B, C for each robot.

## Requirements, Inputs and Deliverables
- The candidate is to develop a model that would allow him to predict forces experienced by the tool-tips, for any path travelled by the robots.
- Four files are provided to help develop this model.
  - Test1.csv, Test2.csv and Test4.csv are data files from 3 different jobs run in our manufacturing cells.
  - A MP4 video file captured during Test4 shows a portion of the run and is provided to help the user visualize the process. You can see more videos of the process on our [website](https://machinalabs.ai).
- Deliverables: Provide a jupyter notebook that includes your understanding of the problem statement, data prep steps, modeling and, evaluation of the effectiveness of your model. Feel free to include markup and charts to make your solution easily undrestood.

## Submission
In order to submit the assignment, do the following:

1. Navigate to GitHub's project import page: [https://github.com/new/import](https://github.com/new/import)

2. In the box titled "Your old repository's clone URL", paste the homework repository's link: [https://github.com/Machina-Labs/machine_learning_hw](https://github.com/Machina-Labs/machine_learning_hw)

3. In the box titled "Repository Name", add a name for your local homework (ex. `machine_learning_soln`)

4. Set privacy level to "Public", then click "Begin Import" button at bottom of the page.

5. Develop your homework solution in the cloned repository and push it to Github when you're done. Extra points for good Git hygiene.

6. Send us the link to your repository.
