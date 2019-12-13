Self-driving vehicles are cars or trucks in which human drivers are
never required to take control to safely operate the vehicle. Also known
as autonomous or driverless cars, they combine sensors and software to
control, navigate, and drive the vehicle.

Though still in its infancy, self-driving technology is becoming
increasingly common and could radically transform our transportation
system (and by extension, our economy and society). Based on automaker
and technology company estimates, level 4 self-driving cars could be for
sale in the next several years.

Various self-driving technologies have been developed by Google, Uber,
Tesla, Nissan, and other major automakers, researchers, and technology
companies.

While design details vary, most self-driving systems create and maintain
an internal map of their surroundings, based on a wide array of sensors,
like radar. Ubers self-driving prototypes use sixty-four laser beams,
along with other sensors, to construct their internal map; Googles
prototypes have, at various stages, used lasers, radar, high-powered
cameras, and sonar.

Software then processes those inputs, plots a path, and sends
instructions to the vehicles actuators, which control acceleration,
braking, and steering. Hard-coded rules, obstacle avoidance algorithms,
predictive modeling, and smart object discrimination (ie, knowing the
difference between a bicycle and a motorcycle) help the software follow
traffic rules and navigate obstacles.

Partially-autonomous vehicles may require a human driver to intervene if
the system encounters uncertainty; fully-autonomous vehicles may not
even offer a steering wheel.

Self-driving cars can be further distinguished as being connected or
not, indicating whether they can communicate with other vehicles and/or
infrastructure, such as next generation traffic lights. Most prototypes
do not currently have this capability.

Autopilot-TensorFlow A TensorFlow implementation of this Nvidia paper
with some changes.

How to Use Download the dataset and extract into the repository folder

Use python train.py to train the model

Use python run.py to run the model on a live webcam feed

Use python run\_dataset.py to run the model on the dataset
