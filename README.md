# interactor-minicpm-vision

An Elixir service that runs a vision-language model through an embedded Python runtime to describe images and video.

## What it is for

A supervised process loads the model once on the GPU and answers single-image, multi-image and video requests with a structured summary, key observations and an interpretation. Prompts are templates under `lib/templates/`.

## Build

```sh
mix deps.get
mix test
```

The model needs a GPU, and the service refuses to start without one.

## Licence

There is no licence file, and the licence is not stated.
