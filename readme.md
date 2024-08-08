<div align="center">
  
![Awesome Machine Learning Elixir logo](https://github.com/georgeguimaraes/awesome-machine-learning-elixir/assets/2929/838443d1-db9c-4285-a261-014894e45695)

# Awesome Machine Learning and Elixir

A curated list of Machine Learning packages and resources for the [Elixir](https://elixir-lang.org/) programming language.

Besides giving an overview for experienced Elixir developers, this list can be useful for ML people looking for other ecosystems.

</div>
<br />

## Contents

- [Computer Vision](#computer-vision)
- [General-Purpose Machine Learning](#general-purpose-machine-learning)
- [Data Analysis / Data Visualization](#data-analysis--data-visualization)
- [Livebooks / Codebases](#livebooks--codebases)
- [Neural Networks](#neural-networks)
- [Resources](#resources)

## Computer Vision

- [Evision](https://github.com/cocoa-xu/evision) - OpenCV bindings for Elixir/Erlang.

## General-Purpose Machine Learning

- [Scholar](https://github.com/elixir-nx/scholar) - Traditional machine learning tools built on top of Nx. Scholar implements several algorithms for classification, regression, clustering, dimensionality reduction, metrics, and preprocessing.
- [EXGBoost](https://github.com/acalejos/exgboost) - Decision Trees implemented using the [XGBoost C API](https://xgboost.readthedocs.io/en/latest/c.html).
- [Mockinjay](https://github.com/acalejos/mockingjay) - Implementation of Microsoft's [Hummingbird](https://github.com/microsoft/hummingbird) library for converting trained Decision Tree models into Nx tensor computations.
- [Ulam](https://github.com/tmbb/ulam_ex) - Elixir interface to [Stan](https://mc-stan.org/), a probabilist programming language.

## Data Analysis / Data Visualization

- [Nx](https://github.com/elixir-nx/nx) - Tensors for Elixir with compilation to CPU/GPU. It is the base for a lot of other libraries.
- [Livebook](https://livebook.dev/) - Write interactive and collaborative notebooks, with integrations to databases, messaging, visualization and more.
- [Explorer](https://github.com/elixir-explorer/explorer) - Series and dataframes for data exploration in Elixir.
- [Kino](https://github.com/livebook-dev/kino) - Render rich and interactive output. Used in Livebook.
- [NxImage](https://github.com/elixir-nx/nx_image) - Image processing in Nx.

## Livebooks / Codebases

- [José Valim's Livebooks](https://github.com/josevalim/livebooks) - Livebooks that José used for talks and Advent of Code.
- [Programming Machine Learning](https://github.com/nickgnd/programming-machine-learning-livebooks) - Livebook notebooks with code examples for the [Programming Machine Learning book by Paolo Perrotta](https://pragprog.com/titles/pplearn/programming-machine-learning/)
- [Machine Learning in Elixir](https://github.com/charlieroth/machine-learning-in-elixir) - Livebooks following along with the book [Machine Learning in Elixir by Sean Moriarity](https://pragprog.com/titles/smelixir/machine-learning-in-elixir/)
- [Asynchoronous Processing in Elixir](https://github.com/whatyouhide/guide_async_processing_in_elixir) - Interactive guide using Livebook to asynchronous data processing in Elixir.

## Neural Networks

- [Axon](https://github.com/elixir-nx/axon) - Neural Networks for Elixir. Built with Nx.
- [Bumblebee](https://github.com/elixir-nx/bumblebee) - Pre-trained neural network models on top of Axon. Provides integration with [Hugging Face](https://huggingface.co/).
- [Ortex](https://github.com/elixir-nx/ortex) - Wrapper around ONNX. Enables you to run ONNX models using Nx.
- [Honeycomb](https://github.com/seanmor5/honeycomb) - Fast LLM inference built on Elixir, Bumblebee, and EXLA.

## Resources

### Books

- [Machine Learning in Elixir - Learning to Learn with Nx and Axon (by Sean Moriarity)](https://pragprog.com/titles/smelixir/machine-learning-in-elixir/)

### Videos

- [(2023) A year in production with Machine Learning on the BEAM](https://www.youtube.com/watch?v=HP86Svk4hzI) (Explorer, Scholar, Bumblebee, Livebook)
- [(2023) Nx-powered decision trees](https://www.youtube.com/watch?v=rbmviKT6HkU) (Nx, EXGBoost)
- [(2023) Building AI apps with Elixir](https://www.youtube.com/watch?v=TfZI5-oQSqI)
- [(2023) MLOps in Elixir: Simplifying traditional MLOps with Elixir](https://www.youtube.com/watch?v=6aVnwj8WQq4) (Nx, Bumbleblee)
- [(2023) Fine-tuning language models with Axon](https://www.youtube.com/watch?v=-iZIZHgHa5M) (Axon)
- [(2023) Data wrangling with Livebook and Explorer](https://www.youtube.com/watch?v=U6nuPjyAUPw) (Livebook, Explorer)
- [(2022) The Future AI Stack by Chris Grainer](https://www.youtube.com/watch?v=Y2Nr4dNu6hI) (Explorer, Axon)
- [(2022) Announcing Bumblebee: pre-trained machine learning models for GPT2, StableDiffusion, and more](https://www.youtube.com/watch?v=g3oyh3g1AtQ) (Livebook, Bumblebee)
- [(2022) Axon: functional programming for deep learning](https://www.youtube.com/watch?v=NWXSiZ-vi-o) (Axon)

### Articles

- (2023) [From Python to Elixir Machine Learning](https://www.thestackcanary.com/from-python-pytorch-to-elixir-nx/) - Nice wrapup on what you gain from the Elixir ecosystem for Machine Learning.

## Contributions

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

This project is licensed under the [CC0 License](LICENSE.md). Feel free to use, share, and adapt the content.
