# lym_tensorboard
This is a simple example which is showed in tensorboard.


# Usage
Before running TensorBoard, make sure you have generated summary data in a log directory by creating a summary writer:
``` python
python tensorboard.py
```

then you can run:
``` bash
tensorboard --logdir lym_logs
```

where the `--logdir` argument is the parent directory to where the data for all of your backtest runs will be saved. Go to [http://localhost:6006](http://localhost:6006) and you should see this:

the loss showed in the SCALARS like this:

![_config.yml](https://github.com/lym0302/lym_tensorboard/blob/master/loss.png)

the main graph showed in the GRAPHS like this:

![_config.yml](https://github.com/lym0302/lym_tensorboard/blob/master/pictures/layer.png)
