# free-space

## Inspiration
Frustrated by time after time of having difficulty finding open study carrels in the library, we set out to build a new platform for us students to intuitively visualize open spots. Inspired by the Laundry view, a service within the laundry system which tracks the state of washers and dryers all across campus, we created Free Space, combining both hardware and software in an easy to use and easy to adapt system not only for tracking study carrel openings, but to find free space anywhere, such as music practice rooms, with just the switch of a sensor.

## What it does
On the hardware side, our current implementation allows users to decide between using light or sound to determine whether or not the space is occupied. A key feature of our devices is that it is extremely easy to switch sensors and subsequently see those changes updated online, allowing for flexible usage. The particular kind of sensor attached is automatically detected by our software and immediately updated on the user interface to reflect these changes.

On the software side, users can currently visit our website and see which study carrels are occupied and which are free. They can also mouse over individual carrels to see other information, such as how long the carrel has been in its current state and how long ago the carrel's state was checked.

## How we built it
On the hardware side, Free Space uses the Electric Imp platform to connect our sensors to the internet. The hardware is split into parts: the main module and the sensor. The main module includes the Electric Imp and associated data and power input lines, while the sensors have power input connections and data out lines. Any sensor capable of transmitting its information over one line is a potential candidate for use with the module and subsequently our software platform, providing flexibility unmatched by any single-sensor system.

On the software side, we used Javascript, HTML, and CSS with the Meteor framework to build a reactive site.

## Challenges we ran into
None of us had worked with electric imp or done webdev before, so just getting started was a challenge.

## Accomplishments that we're proud of
We did it! We actually were able to complete our goal of linking the sensors to markers on the library map and update the data in real time.

## What we learned
Hackathons are great.

## What's next for Free-Space
We believe that our site has the potential to be a helpful tool for students, so we'd love to collaborate with the libraries on campus and give it a trial run. In addition, we wrote the code and built the hardware with flexibility in mind, so anyway can tweak our hardware and software to suit their needs. For example, free-space can easily be used to check the availability of music rooms using sound sensors.

