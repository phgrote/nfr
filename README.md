# Neural Field Representations of Articulated Objects for Robotic Manipulation Planning

## Abstract
Traditional approaches for manipulation planning
rely on an explicit geometric model of the environment to
formulate a given task as an optimization problem. However,
inferring an accurate model from raw sensor input is a hard
problem in itself, in particular for articulated objects (e.g., closets,
drawers). In this paper, we propose a Neural Field Represen-
tation (NFR) of articulated objects that enables manipulation
planning directly from images. Specifically, after taking a few
pictures of a new articulated object, we can forward simulate
its possible movements, and, therefore, use this neural model
directly for planning with trajectory optimization. Additionally,
this representation can be used for shape reconstruction, semantic
segmentation and image rendering, which provides a strong
supervision signal during training and generalization.
We show that our model, which was trained only on synthetic
images, is able to extract a meaningful representation for unseen
objects of the same class, both in simulation and with real
images. Furthermore, we demonstrate that the representation
enables robotic manipulation of articulated object in the real
world directly from images.
