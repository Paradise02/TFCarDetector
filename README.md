### training

    $ python model_main.py --pipeline_config_path=./models/pipeline.config
    --model_dir=./models
    --num_train_steps=20000
    --sample_1_of_n_eval_examples=1
    --alsologtostderr

### open tensorboard

    $ python -m tensorboard.main --logdir=./models --host localhost --port 8000

### export frozen graph

    $ python export_inference_graph.py --input_type=image_tensor
    --pipeline_config_path=./models/pipeline.config
    --trained_checkpoint_prefix=./models/model.ckpt-$NO_STEP$
    --output_directory=./models/output