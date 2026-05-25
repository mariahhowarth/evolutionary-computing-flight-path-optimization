# Climate-Aware Aircraft Route Optimization Using a Genetic Algorithm

This repository contains my evolutionary computing project for optimizing aircraft flight paths using a genetic algorithm.

The project models a simplified airspace grid with contrail-risk regions, wind-effect zones, and restricted airspace. The genetic algorithm evolves candidate flight routes and minimizes a route cost function based on distance, contrail exposure, wind benefit, smoothness, and restricted-zone penalties.

## Files

- `climate_aware_flight_path_ga.ipynb` — main Jupyter notebook with code, results, and explanations
- `climate_aware_flight_path_ga.html` — exported readable version of the notebook

## Project Summary

The goal is to demonstrate how evolutionary computing can be used to solve a real-world optimization problem. The genetic algorithm compares optimized routes against a direct-route baseline and a random-search baseline, then evaluates how mutation rate and population size affect route performance.
