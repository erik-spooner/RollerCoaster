#  Animation Assignment 1 - Rollercoaster

The purpose of this assignment is to create a realistic model of rollercoaster running a track. 

The track was created by placing control points for a degree 4 closed NURBS (Non-Uniform Ration B-Spline) curve. The movement of the carts on the track is split into three parts. Initially the cart is given a constant acceleration up to the highest point on the track, from here the speed of the cart is controlled by gravity where gravitational potential energy is converted into kinetic energy from which the velocity of the cart is calculated. Finally in the last portion of the track (~5%) a deceleration is applied to slow down the cart untill it reaching its initial position agian. 

Another goal of this assignment was to ensure that while on the ride all the force that passengers experience comes up through the feet (i.e. there is no tangential force acting upon them.), the result of this is that the track must be perpendicular to sum of forces acting upon the cart at that postion. In this there are two forces that can be felt by the passenger, the first is gravity, while the second is the centrifugal force that is experienced when travelling around a curve in the track. The centrifugal force is the same magnitude but oposite direction of the centripetal force 

