# Object-Detection-Train-Test-Split
When you have image data and corresponding xml files, this script will help in splitting the data in two folders - train and test

Usage:
python train_test_split.py \
        --datadir='images/all/' \
        --split=0.1 \
        --train_output='images/train/' \
        --test_output='images/test/'
