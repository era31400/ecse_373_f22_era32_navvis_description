To run:

Use: roslaunch navvis\_description navvis\_description.launch

Still need to use: rosparam set /robot\_description -t urdf\_from_xacro.urdf
rosparam set /my_\robot -t urdf\_from\_xacro.urdf

For wheels to appear: rosrun joint\_state\_publisher\_gui joint\_state\_pulblisher\_gui &
