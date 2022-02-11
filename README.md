## ApeGNN: Adaptive Aggregation and Pooling in GNNs for Recommendation

This is our PyTorch implementation for the paper:

## run
python main.py --dataset Amazon --context_hops 3 --gpu_id 0 --gnn ApeGNN --pool sum --t_u 1 --t_i 3

## Environment Requirement

The code has been tested running under Python 3.7.6. The required packages are as follows:

- pytorch == 1.7.0
- numpy == 1.18.2
- scipy == 1.4.1
- sklearn == 0.24.1
- prettytable == 2.1.0


## Dataset

We use three processed datasets: AMiner, Gowalla, Yelp2018 and Amazon.

|     Dataset   | #Users   | #Items   | #Interactions   | Density  |
| ------------- | ------- | --------- | --------- |--------- |
|AMiner    | 5,340    | 14,967    | 163,084          | 0.00204 | 
|Gowalla   | 29,858   | 40,981    | 1,027,370        | 0.00084 | 
|Yelp2018  | 31,668   | 38,048    | 1,561,406        | 0.00130 | 
|Amazon    | 192,403  | 63,001    | 1,689,188        | 0.00014 | 