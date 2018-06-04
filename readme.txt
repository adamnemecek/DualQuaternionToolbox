The goal of this toolbox is to provide dual quaternion methods, and use them in the framework of kinematics.  
Everyone is invited to participate to the toolbox by including its own method, which fits the toolbox standards.
If you want your method incorporated in this toolbox (with due acknowledgement), send us an email to the address below.

Getting started: 
* Please refer to the document "Install.txt" which is located in the same folder as this "readme.txt" file.
* The toolbox provides many methods (functions) to:
   - encode dual quaternions: a point position, velocity, a line position, velocity, a rotation, a translation, a screw,...
   - do operations on dual quaternions: the dual quaternion multiplication, the dual quaternion conjugates, the inverse,...
   - retrieve parameters from a dual quaternion: finding the parameters of a rotation dual quaternion, or a screw dual quaternion,...
   - easily going back and forth between Fick rotation coordinates, 3*3 rotation matrices, rotation dual quaternions, angular vector
   - find the shortest rotation between two unitary vecors
   - find the shortest screw motion between two lines (it answers if two lines intersect, and if relevant, what the intersection point is)
* The toolbox also provides 1 example file (example_forward_kinematics.m) (see also the file "html/example_forward_kinematics.html"). This
example describes the forward kinematics of the end-effector of a two- or three-link arm in 3D space. The user can choose between two methods 
(alternating rotation and translation dual quaternions, or using screw motion dual quaternions) to encode the forward kinematics: the results are
identical, whatever the method which is used. Furthermore, for the three-link arm, the orientation of the end-effector is also taken into account
(via line transformations).
* For each of these methods and example, the user will find an extensive documentation by typing HELP NAME_OF_THE_FUNCTION in the MATLAB environment  

It was implemented by Guilllaume Leclercq, Philippe Lefèvre and Gunnar Blohm.

Reference: Leclercq, G., Lefèvre, P. , Blohm, G. (2012). 3D kinematics using dual quaternions: theory and applications in neuroscience, 
submitted to Frontiers in behavioral Neuroscience

It is a beta version, please report any bug, comment or suggestion to gu.leclercq@gmail.com