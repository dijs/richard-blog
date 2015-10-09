title: 2D Enviornment
tags:
---

# Goal

I like the idea of simulating large words down to the smallest detail. As I do not know where to start with such a large venture, I will start small. My goal is to create a finite 2 dimensional environment which is ever changing from gravity and weather. Water and soil will be my primary components starting out.

# Setup

- Create 2d canvas to draw on (DONE)
- Create random soil landscape (DONE)
- Use fun colors :) (DONE)
- Create rainfall (DONE)
- Accumulate and smooth water (DONE)
- Evaporation! (DONE)
- Need water flow...
- No random rain, use humidity formulas
- Create water erosion by frame, soil should have a moisture attribute (DONE)

# Ideas

[Learn!](http://www-cs-students.stanford.edu/~amitp/simblob/economy.html#geography)

- Areas near rivers have moist soil; areas far from rivers have dry soil. Moisture affected vegetation. Vegetation slows water flow.
- Rain creates water in all places, some of the time. It then flows downhill. Then it evaporates and is absorbed by the ground. The rain carves out river channels.
- Springs create water all the time, but only in a few locations. The springs keep the river channels filled. I didn't simulate rock layers or groundwater flow; I just placed springs randomly on mountains.
- Flowing water has momentum. If I remember right, this was important for making rivers meander.
- Fast moving water picks up sediment; slow moving water deposits sediment ahead of it. This carves out river valleys.
- During initial map creation I accelerated the water flow and erosion; during gameplay it ran at normal speed.

:BLOG POST LIMIT

- Simulate plant life
- Simulate trees...

:BLOG POST LIMIT

- Simulate human colonies