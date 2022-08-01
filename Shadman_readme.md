python src/train_tripletloss.py --logs_base_dir ~/logs/facenet/ --models_base_dir ~/models/facenet/ --data_dir E:/Datasets/BeardVsNonBeard/struct_for_tri_loss_train__mtcnnpy_182 --image_size 160 --model_def models.inception_resnet_v1  --optimizer RMSPROP --learning_rate 0.01 --weight_decay 1e-4 --max_nrecay 1e-4 --max_nrof_epochs 500 --people_per_batch 20 --images_per_person 30


Check the wiki's triplet loss for more, almost all info is given there

https://www.tensorflow.org/addons/tutorials/losses_triplet