# 241B: Benefits and Tradeoffs of Utilizing Systolic Arrays in Training/Inference with bFloat16
## Anson and Ryan

## Project Abstract

With machine learning (ML) becoming an essential component of modern commercial products, researchers have sought to optimize both software and hardware in order to support faster and more energy efficient inference. Recently, a new float format named bfloat16 was adopted for training/inference optimization. By having 1 sign, 8 exponent, and 7 explicit mantissa bits, bfloat16 is able to preserve the approximate dynamic range of float32 while having the area footprint of a float16. Moreover, research has shown that the truncation of mantissa bits have minimal effect on the accuracy of models. This has many cost saving implications, as models now use less space and more data can be transferred/computed per cycle. In our research project, we will evaluate the benefits and tradeoffs of utilizing bfloat16 in ML training/inference workloads using systolic arrays. To gather data, we plan on using Gemmini, a systolic array generator, coupled with Rocket Chip and the BOOM out-of-order processor to run various workloads that compare the accuracy, performance, and resource utilization of using bfloat16 versus other number formats such as float32 and integer8. 

### Full Link
[Project Abstract](https://docs.google.com/viewer?url=https://github.com/TsaiAnson/241b_project/raw/master/Project%20Abstract.pdf)


## Midterm Report
Currently in progress.

## Final Report

## Other
