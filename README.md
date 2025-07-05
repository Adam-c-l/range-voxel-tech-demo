# range-voxel-tech-demo
A 3x3 grid-based block placement system designed for building machines and managing an advanced item and machine progression system. Built with the Range Engine, this project demonstrates precise block placement mechanics alongside a tech tree for unlocking increasingly complex machines and items.

<p align="center">
  <img src="showcase/placing.png" alt="3x3 grid preview" />
</p>

When a block is placed, the system checks whether the new configuration of blocks matches any predefined machine blueprint. This system only checks for machine formation when a block is placed, and only around that specific block. This makes the system scalable and modular.

<p align="center">
  <img src="showcase/machine_show.png" alt="machine example" />
</p>
rotations are now easy since you always check from the placed block
