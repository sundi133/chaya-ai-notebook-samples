# image_classification
image_classification with chaya-ai integration
cai.model_name = "deep_learning_adam_optimizer_loss_SparseCategoricalCrossentropy"
cai.save({"train":"start"})
cai.save({"metric_type":"test", "metrics":{"accuracy":val_acc[len(val_acc)-1]}})
cai.saveplot("/content/accuracy_loss_per_epoch.png")

# Run multiple models with tweaks on model or data and track all your changes with one time integration.
https://app.chaya.ai/projects/image_classification/ for keeping track of trial results & progress in time series

![Alt text](assets/cplots.png?raw=true "Title")
![Alt text](assets/ctrials.png?raw=true "Title")

