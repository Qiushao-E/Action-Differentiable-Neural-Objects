# ∂Oθ: Action-Differentiable Neural Objects

## Reconstruction

Keypoint projections and reconstructed geometry for 10 rigid objects, 10 skinned objects, and 10 soft bodies.

### Rigid objects

| Cabinet | Clamp |
| :---: | :---: |
| [![Cabinet](media/reconstruction/rigid/cabinet.gif)](media/reconstruction/rigid/cabinet.png) | [![Clamp](media/reconstruction/rigid/clamp.gif)](media/reconstruction/rigid/clamp.png) |

| Folding Rule | Microwave |
| :---: | :---: |
| [![Folding Rule](media/reconstruction/rigid/foldingrule.gif)](media/reconstruction/rigid/foldingrule.png) | [![Microwave](media/reconstruction/rigid/microwave.gif)](media/reconstruction/rigid/microwave.png) |

| Faucet | Storage Furniture |
| :---: | :---: |
| [![Faucet](media/reconstruction/rigid/partnet_faucet_1370.gif)](media/reconstruction/rigid/partnet_faucet_1370.png) | [![Storage Furniture](media/reconstruction/rigid/partnet_storagefurniture_46403.gif)](media/reconstruction/rigid/partnet_storagefurniture_46403.png) |

| Sliding Window | Pliers |
| :---: | :---: |
| [![Sliding Window](media/reconstruction/rigid/partnet_window_103051.gif)](media/reconstruction/rigid/partnet_window_103051.png) | [![Pliers](media/reconstruction/rigid/pliers.gif)](media/reconstruction/rigid/pliers.png) |

| Tripod | XHand |
| :---: | :---: |
| [![Tripod](media/reconstruction/rigid/tripod.gif)](media/reconstruction/rigid/tripod.png) | [![XHand](media/reconstruction/rigid/xhand_right.gif)](media/reconstruction/rigid/xhand_right.png) |

### Skinned objects

| Bovidae | Canidae |
| :---: | :---: |
| [![Bovidae](media/reconstruction/skinning/smal_bovidae.gif)](media/reconstruction/skinning/smal_bovidae.png) | [![Canidae](media/reconstruction/skinning/smal_canidae.gif)](media/reconstruction/skinning/smal_canidae.png) |

| Canidae II | Equidae |
| :---: | :---: |
| [![Canidae II](media/reconstruction/skinning/smal_canidae_02.gif)](media/reconstruction/skinning/smal_canidae_02.png) | [![Equidae](media/reconstruction/skinning/smal_equidae.gif)](media/reconstruction/skinning/smal_equidae.png) |

| Equidae II | Felidae |
| :---: | :---: |
| [![Equidae II](media/reconstruction/skinning/smal_equidae_02.gif)](media/reconstruction/skinning/smal_equidae_02.png) | [![Felidae](media/reconstruction/skinning/smal_felidae.gif)](media/reconstruction/skinning/smal_felidae.png) |

| Felidae II | Hippopotamidae |
| :---: | :---: |
| [![Felidae II](media/reconstruction/skinning/smal_felidae_02.gif)](media/reconstruction/skinning/smal_felidae_02.png) | [![Hippopotamidae](media/reconstruction/skinning/smal_hippopotamidae.gif)](media/reconstruction/skinning/smal_hippopotamidae.png) |

| SMPL Female | SMPL Male |
| :---: | :---: |
| [![SMPL Female](media/reconstruction/skinning/smpl_female.gif)](media/reconstruction/skinning/smpl_female.png) | [![SMPL Male](media/reconstruction/skinning/smpl_male.gif)](media/reconstruction/skinning/smpl_male.png) |

### Soft bodies

| Pink cloth | Dog plush |
| :---: | :---: |
| [![Pink cloth](media/reconstruction/softbody/008-pink-cloth.png)](media/reconstruction/softbody/008-pink-cloth.png) | [![Dog plush](media/reconstruction/softbody/043-dog.gif)](media/reconstruction/softbody/043-dog.png) |

| Cat plush | Soft cube |
| :---: | :---: |
| [![Cat plush](media/reconstruction/softbody/045-cat.gif)](media/reconstruction/softbody/045-cat.png) | [![Soft cube](media/reconstruction/softbody/051-cube.png)](media/reconstruction/softbody/051-cube.png) |

| Makeup sponge | Striped rope |
| :---: | :---: |
| [![Makeup sponge](media/reconstruction/softbody/056-makeup-sponge.png)](media/reconstruction/softbody/056-makeup-sponge.png) | [![Striped rope](media/reconstruction/softbody/081-stripe-rope.png)](media/reconstruction/softbody/081-stripe-rope.png) |

| Watermelon | Octopus plush |
| :---: | :---: |
| [![Watermelon](media/reconstruction/softbody/095-watermelon.gif)](media/reconstruction/softbody/095-watermelon.png) | [![Octopus plush](media/reconstruction/softbody/096-octopus.png)](media/reconstruction/softbody/096-octopus.png) |

| Croissant plush | Sheep plush |
| :---: | :---: |
| [![Croissant plush](media/reconstruction/softbody/121-croissant-plush.gif)](media/reconstruction/softbody/121-croissant-plush.png) | [![Sheep plush](media/reconstruction/softbody/164-sheep.gif)](media/reconstruction/softbody/164-sheep.png) |

## Grasp optimization

Grasp optimization on the duck with ∂Oθ, Fast-Grasp’D, and DexGraspNet.

![Grasp optimization comparison](media/optimization/duck-comparison.png)

![Optimization trajectories and grasp configurations](media/optimization/duck-optimization.gif)

## Real-world execution

Duck grasping with π0.5, ∂Oθ, and MuJoCo policies at in-distribution (ID) and out-of-distribution (OOD) positions.

![Duck grasping policy comparison](media/execution/duck-comparison.png)

| Policy | In-distribution | Out-of-distribution |
| :---: | :---: | :---: |
| π0.5 | [![π0.5 · ID](media/execution/pi05-id.gif)](media/execution/pi05-id.mp4) | [![π0.5 · OOD](media/execution/pi05-ood.gif)](media/execution/pi05-ood.mp4) |
| ∂Oθ | [![∂Oθ · ID](media/execution/ours-id.gif)](media/execution/ours-id.mp4) | [![∂Oθ · OOD](media/execution/ours-ood.gif)](media/execution/ours-ood.mp4) |
| MuJoCo | [![MuJoCo · ID](media/execution/mujoco-id.gif)](media/execution/mujoco-id.mp4) | [![MuJoCo · OOD](media/execution/mujoco-ood.gif)](media/execution/mujoco-ood.mp4) |

[π0.5 ID video](media/execution/pi05-id.mp4) · [π0.5 OOD video](media/execution/pi05-ood.mp4) · [∂Oθ ID video](media/execution/ours-id.mp4) · [∂Oθ OOD video](media/execution/ours-ood.mp4) · [MuJoCo ID video](media/execution/mujoco-id.mp4) · [MuJoCo OOD video](media/execution/mujoco-ood.mp4)
