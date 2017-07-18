# image_classification_tensorflow

At first, download the repo and then run the simple retrain.py with below command:

```sh
python retrain.py --bottleneck_dir=bottlenecks --how_many_training_steps=500 --model_dir=inception --summaries_dir=training_summaries/basic --output_graph=retrained_graph.pb --output_labels=retrained_labels.txt --image_dir=Images
```

Then try to run retrain_modified.py which restores the model from the checkpoint.
