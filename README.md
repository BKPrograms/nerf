# nerf
An implementation of Neural Radiance Fields for Novel Views (https://arxiv.org/pdf/2003.08934.pdf)

A neural network that attempts to learn and render a 3D scene from 2D views of the scene. The model relies on 2D views and the camera extrinsic matrices of each view,
which are used to fire camera rays through the scene where an MLP learns off the colours of the rays. Once the 3D world has been learned, we can use it to generate
new 2D views we have not seen before.

# Training video:
## A video of the model training:
https://user-images.githubusercontent.com/68819197/233864194-7388c6ba-0471-41fb-83c2-74faba9fbfdc.mp4

# Final results after 2.5k iterations:
## Comparison with an existing view:
![image](https://user-images.githubusercontent.com/68819197/233864309-a9079515-9095-4093-8539-df494518b227.png)

## New orbiting views (all generated by the model):


https://user-images.githubusercontent.com/68819197/233864663-e9b9fb4f-1f61-4a70-bb7f-c0ca3720cdbb.mp4



https://user-images.githubusercontent.com/68819197/233864668-2fe20d3b-8a32-4978-a978-377a002444c3.mp4

