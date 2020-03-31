# IGVC Gazebo Maps
2020 Senior Design - IGVC Maps

## Usage
Example command:
```
roslaunch igvc_gazebo qualification.launch
```

### Command-line configurable items
Both Gazebo and rviz GUIs can be turned on/off using `gazebo_gui` and `rviz_gui`. *Both currently default to true.* Even if you turn `gazebo_gui` off, Gazebo itself will still run. Currently, rviz defaults to a file in the path `igvc_description/rviz/<launch file name>`.

Example command:
```
roslaunch igvc_gazebo qualification.launch gazebo_gui:=false
```

## How to install

* Remove your `igvc_gazebo` directory (move it to another directory if you have changes you don't want to lose)
* Add the submodule: `git submodule add https://github.com/RyanSchw/igvc_gazebo_maps igvc_gazebo`
  * This clones the repository to a new igvc_gazebo folder. *You must leave the folder name as igvc_gazebo for the paths to work. If this is not the naming convention you follow, let me know.*
* Commit and push your changes (it should be `.gitmodules` and `igvc_gazebo`

# Sources
Original maps sourced from https://github.com/RoboJackets/igvc-software.
