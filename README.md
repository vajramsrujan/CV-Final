Code credit goes to: 
https://github.com/gordicaleksa/pytorch-neural-style-transfer-johnson

The code for this report was forked from this repository. The key changes made were in 
1. perceptual_loss_net.py: Added MobilNetv3 class, exposed intermediate maps. 

2. training_script.py: Adapted what maps were being used to compute content and style loss after setting the loss_network to MobilNetv3. 

3. A new script addition called test.py to plot the intermediate representations. 
