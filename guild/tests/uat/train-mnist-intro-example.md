# Train `mnist-intro` example

We can train the MNIST example model `mnist-intro` in the `mnist`
directory:

    >>> run("guild -C examples/mnist run intro:train -y --no-gpus epochs=1", timeout=120)
    Masking available GPUs (CUDA_VISIBLE_DEVICES='')
    Resolving data dependency
    ...
    Step 0: training=...
    Step 0: validate=...
    ...
    Step 540: training=...
    Step 540: validate=...
    <exit 0>
