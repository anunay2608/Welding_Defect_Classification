# Welding_Defect_Classification(Tensorflow)
## TIG Welding : 
Tungsten Inert Gas (TIG) welding, also known as Gas Tungsten Arc Welding (GTAW)  is an arc welding process that produces the weld with a non-consumable tungsten  electrode. In the TIG welding process the arc is formed between a pointed tungsten  electrode and the workpiece in an inert atmosphere of argon or helium. When filler metal is required, it must be added separately to the  weld pool.  
Welding defects that we are going to consider : 
  1) Burn Through :  localised collapse of the molten pool due to excessive penetration or loss of control, resulting in a hole/cavity in the weld root run.
  2) Contamination : Elongated blow holes or scattered tiny spherical holes in the weld pool. Caused due to evolution of gases during welding.
  3) Lack of Fusion : The pure lack of fusion is a structural defect, where the molten metal sticks to the parent metal which has not melted enough during welding.
  4) Misalignment : It can be due to poor component fit-up or relative motion between the components during the welding process.
  5) Lack of Penetration : Incomplete root fusion occurs when the weld fails to fuse to one side of the root. 

## How Deep Learning helps in Welding_Defects_Classification : 
For the current problem statement of classification of welding defects, we have decided to use the CNN model, which is known to provide promising results with training datasets. A CNN model examines a given image piece by piece, picking up features such as edges, corners, colour variation patterns, etc, creating a feature map, with the help of which it classifies the image (in our case, the five different classes of welding defects). We intend to improve the learning and validation accuracy, converge the network, and reduce our custom loss to minimum with the increasing number of the epochs. Each point of the precision curve means the correct prediction rate for the set of train or validation images.

