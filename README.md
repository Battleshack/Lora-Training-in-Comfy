This is a fork of [LarryJane491's Lora-Training-in-Comfy](https://github.com/LarryJane491/Lora-Training-in-Comfy), which again is based on [Akegarasu's lora-scripts](https://github.com/Akegarasu/lora-scripts) project.

### How this fork differs from the original master branch

Implemented a bugfix for the Advanced node, correcting typing error on line 299 in the train.py file. (_network_moduke_ changed to _network_module_.)
Changed some default parameter for the simple node.
Added Support for regularization dataset. 

**How to add regularization dataset**
Make a folder in the _data_path_ directory, and name this new folder _reg_train_dir_.
