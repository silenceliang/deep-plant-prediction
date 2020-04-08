# deep-plant-prediction

## Configuration 
train/validation 8:2
LR = 1e-2
batch size = 32
patience = 3

#### w/o regirization loss (Resize(256), RandomCrop(224))
accuracy = 0.773

### w regularization 1e-3*l2_loss
accuracy = 0.810

#### w regularization 1e-4*l1_loss 1e-3*l2_loss (Resize(256), RandomCrop(224))
accuracy = 0.641

#### w regularization 1e-4*l1_loss 1e-3*l2_loss (Resize(128), RandomCrop(81))
accuracy = 0.409

#### w regularization 1e-4*l1_loss 1e-3*l2_loss (Resize(128), CenterCrop(81))
accuracy = 0.706

#### w regularization 1e-4*l1_loss 1e-3*l2_loss (Resize(256), CenterCrop(224))
accuracy = 
