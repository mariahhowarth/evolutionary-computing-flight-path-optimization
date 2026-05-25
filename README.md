# Climate-Aware Aircraft Route Optimization Using a Genetic Algorithm

This repository contains my evolutionary computing project for optimizing aircraft flight paths using a genetic algorithm.

The project models a simplified airspace grid with contrail-risk regions, wind-effect zones, and restricted airspace. The genetic algorithm evolves candidate flight routes and minimizes a route cost function based on distance, contrail exposure, wind benefit, smoothness, and restricted-zone penalties.

## Files

- `climate_aware_flight_path_ga.ipynb` — main Jupyter notebook with code, results, and explanations

## Abstract

Aircraft route planning involves several competing objectives. A direct route may minimize distance and fuel use, but it may also pass through atmospheric regions where persistent contrails are more likely to form. Because contrails can contribute to aviation climate impact, a more climate-aware route may sometimes require a controlled detour.

This project implements a genetic algorithm to search for optimized aircraft routes in a simulated two-dimensional airspace. Each candidate solution is represented as a sequence of intermediate waypoints between an origin and destination. The algorithm evaluates each route using a cost function that includes distance, contrail-risk exposure, wind effects, route smoothness, and restricted airspace penalties.

The optimized route is compared against a direct-route baseline and a random-search baseline. Additional experiments test how mutation rate and population size affect the final route cost.
