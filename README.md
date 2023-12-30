# make_circles

The `make_circles` function in the `datasets.py` module generates a dataset of points arranged in concentric circles. It allows for the creation of balanced or unbalanced samples, with the option to add noise and additional features.

## Mathematics Behind the Algorithm

The `make_circles` function uses the concept of polar coordinates to generate points in concentric circles. Each point is defined by a radius and an angle, with the radius determined by a random uniform distribution and the angle by a random distribution over [0, 2π]. The function also allows for the addition of Gaussian noise to the generated points.

## Pseudocode of the Algorithm

```
1. Initialize the number of samples, noise level, random state, number of circles, balance flag, and number of features.
2. Create balanced or unbalanced samples.
3. Generate target values.
4. For each circle, generate points using polar coordinates and add them to the dataset.
5. If the number of features is greater than 2, generate additional features.
6. Add Gaussian noise to the dataset.
7. Return the dataset and target values.
```

## Modules

The project contains two modules:

1. `datasets.py`: Contains the `make_circles` function for generating the dataset.
2. `plots.py`: Contains the `scatter2D` and `scatter3D` functions for visualizing the dataset.

## Notebook

A Jupyter notebook demonstrating the usage of the `make_circles` function and the visualization functions is included in the repository.

## Usage

To use the `make_circles` function, import it from the `datasets` module and call it with the desired parameters. The function returns a dataset and corresponding target values, which can be visualized using the `scatter2D` or `scatter3D` functions from the plots module.

## Contributing

Contributions to the project are welcome. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.



