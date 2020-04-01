# Comparing Reduced Bitwidth Representations forMachine Learning - Quantization vs Brain Float
## Anson and Ryan

## Project Abstract

Machine learning (ML) has rapidly become an essential component of modern commercial products. As such, researchers have sought to optimize both software and hardware in order to support faster and more energy efficient training and inference, both on the warehouse scale and for mobile devices. A recent area of focus is to use reduced bit-width numerical representation for weights and activations. One technique to reduce bitwidth is quantization, or using narrow integers along with a scaling factor in the place of a wider float value. An alternative technique is to use a novel numerical representation, such as the 16 bit bFloat format (bf16). With 1 sign, 8 exponent, and 7 explicit mantissa bits, bf16 is able to preserve the approximate dynamic range and model accuracy of a 32-bit floating point (fp32) network while consuming half the space. In this project, we will compare the impacts on accuracy, performance, and resource utilization of these reduced bitwidth methods by running a testbench of ML workloads on a Gemmini generated systolic array coupled with Rocket Core in-order and BOOM out-of-order processors.

### Full Link
[Project Abstract](https://docs.google.com/viewer?url=https://github.com/TsaiAnson/241b_project/raw/master/Project%20Abstract.pdf)


## Midterm Report
[Midterm Report](https://docs.google.com/viewer?url=https://github.com/TsaiAnson/241b_project/raw/master/Midterm%20Report.pdf)

## Final Report

## Other
