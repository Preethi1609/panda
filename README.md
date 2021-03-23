# panda
Launch RViz:
roslaunch panda_moveit_config demo.launch

Run the Python code:
rosrun moveit_tutorials move_group_python_interface_tutorial.py

In RViz, we should be able to see the following:

Press <enter> in the shell terminal where you ran the rosrun command in between each step

        The robot plans and moves its arm to the joint goal.
        The robot plans a path to a pose goal.
        The robot plans a Cartesian path.
        The robot displays the Cartesian path plan again.
        The robot executes the Cartesian path plan.
        A box appears at the location of the Panda end effector.
        The box changes colors to indicate that it is now attached.
        The robot plans and executes a Cartesian path with the box attached.
        The box changes colors again to indicate that it is now detached.
        The box disappears.

