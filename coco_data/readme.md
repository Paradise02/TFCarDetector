create coco TF record

Put the extracted coco annotations and images in corresponding folder, and run the following command.

python create_coco_tf_record.py --logtostderr --train_image_dir="./train2014" --val_image_dir="./eval2014_" --test_image_dir="./test2014" --train_annotations_file="./annotations/instances_train2014.json" --val_annotations_file="./annotations/instances_val2014.json" --output_dir="./output"