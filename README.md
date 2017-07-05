# makeup-removal
our code based on https://github.com/affinelayer/pix2pix-tensorflow
                 
                 https://github.com/duxingren14/DualGAN
                  
Train the model in first step:

python main.py --phase train --dataset_name dataset_name  --use_labeled_data True 
Train the model in second step:

python main.py --phase train --dataset_name dataset_name  --use_labeled_data False 



Test the model:

python main.py --phase test --dataset_name dataset_name
