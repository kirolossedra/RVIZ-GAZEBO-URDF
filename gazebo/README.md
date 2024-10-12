# First: Adding Inertias Specifications




### 1. The 3d inertia tensor table for each usable shape in rviz urdf
<table>
  <thead>
    <tr>
      <th>Shape</th>
      <th>Moment of Inertia Tensor</th>
      <th>Variables</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Solid Sphere</strong></td>
      <td>
        
```math
 \begin{bmatrix} \frac{2}{5} m r^2 & 0 & 0 \\ 0 & \frac{2}{5} m r^2 & 0 \\ 0 & 0 & \frac{2}{5} m r^2 \end{bmatrix}
 ```
 </td>
      <td>\(m\): Mass of the sphere, \(r\): Radius of the sphere</td>
    </tr>
    <tr>
      <td><strong>Rectangular Box</strong></td>
      <td>
        
```math
  \begin{bmatrix} \frac{1}{12} m (h^2 + d^2) & 0 & 0 \\ 0 & \frac{1}{12} m (w^2 + h^2) & 0 \\ 0 & 0 & \frac{1}{12} m (w^2 + d^2) \end{bmatrix}\
```
  </td>
      <td>\(m\): Mass of the box, \(a\): Length along \(x\)-axis, \(b\): Width along \(y\)-axis, \(c\): Height along \(z\)-axis</td>
    </tr>
    <tr>
      <td><strong>Solid Cylinder</strong></td>
      <td>
        
        
        
  ```math
  \begin{bmatrix} \frac{1}{12} m (3r^2 + h^2) & 0 & 0 \\ 0 & \frac{1}{12} m (3r^2 + h^2)  & 0 \\ 0 & 0 & \frac{1}{12} m r^2 \end{bmatrix}\
 ```

</td>
      <td>\(m\): Mass of the cylinder, \(r\): Radius of the base, \(h\): Height of the cylinder</td>
    </tr>
  </tbody>
</table>


# Second: Creating a launch file to launch gazebo/+ our robot

# Third: Publishing to cmd/vel to move the robot
```
ros2 topic pub /cmd_vel geometry_msgs/Twist '{linear: {x: 0.5}, angular: {z: 0.0}}' to make robot move in gazebo

```
![ezgif-1-e8a803aeea](https://github.com/user-attachments/assets/bf2b2d43-534c-450e-b4cb-fe3faf740a1e)


