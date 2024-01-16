# FoodX-251

Sandro Erba  856327

Elia Gaviraghi 869493

## Folder Structure 

```
┣ 📂 progetto \                                # Root directory
┣ ┣ 📂 dataset\                                # training and test set CSV
┣ ┃ ┣ 📄 train_info_clean.csv                  # training set CSV after cleaning 
┣ ┃ ┣ 📄 train_info_dirty.csv                  # original CSV
┣ ┃ ┣ 📄 val_info.csv                          # test set CSV
┣ ┣ 📂 matlab_script\                 
┣ ┃ ┣ 📄 alex_net_on_validation.m
┣ ┃ ┣ 📄 clean_and_augment_dataset.m
┣ ┃ ┣ 📄 clustering_features.m                 # script for cleaning dirty dataset
┣ ┃ ┣ 📄 from_folder_to_subfolder.m            # obtain foldering dataset from the original dataset
┣ ┃ ┣ 📄 from_subfolder_to_one_folder.m        # the inverse process
┣ ┣ 📂 notebook\                               # colab files
┣ ┃ ┣ 📄 MobileNetV3.ipynb                     # main notebook where we fine-tuning the selected model
┣ ┃ ┣ 📄 Category_Search_foodx251.ipynb        # category search with selected method using our fine-tuned model
┣ ┃ ┣ 📄 Category_Search_foodx251_cheat.ipynb  # a little bit alternative method for category search
┣ ┃ ┣ 📄 Category_Search_imagenet.ipynb        # inital and alternative method with CNN trained on ImageNet
