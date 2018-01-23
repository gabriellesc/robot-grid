# Automated warehouse simulation
> **Simulation of robots intelligently moving towards goals/around obstacles (based on [Amazon warehouse robots](https://raw.githubusercontent.com/gabriellesc/gabriellesc.github.io/master/robotGrid/AmazonWarehouseRobots.mp4))**

## Premise

*Note*: This is based on a series of [assignments](https://github.com/csc301-fall-2016/a5-fake2) from Joey Freund's 2016 "Introduction to Software Engineering" [course](https://csc301-fall-2016.github.io/) at the University of Toronto (although the assignments were written in Java rather than JavaScript).

A grid can be used to represent the floor plan of a warehouse. Grid cells can contains [racks](https://www.bing.com/images/search?q=warehouse+racks&go=Search&qs=n&form=QBILPG&pq=warehouse+racks&sc=8-15&sp=-1&sk=).

For example, below is a floor plan of a small, rectangular warehouse containing a few racks.

![Simple floor plan](https://csc301-fall-2016.github.io/resources/warehouse-floor-plan.png)

Robots can move "vertically" and "horizontally" in the grid. A robot may have a destination/goal cell that it attempts to reach.

Where there are multiple robots with goals,
- the path from each robot to its goal is planned, and
- multiple robots attempt reach their goals in parallel

### Additional Requirements
- All robots get to their destination, whenever it is possible
- Robots don’t crash into walls or into one another
- Robots do not take unnecessarily long paths
- Robots do not stand idle when they can move and get closer to their destination

## How it works

- React + Redux
- path planning algorithm
- robot movement animation

## License
Licensed under the MIT License. See [LICENSE](license) for more information.
