# Power-Efficient-Sparse-Aware-Neural-Network-Accelerator-using-Systolic-Array-
The growing requirement of deep learning algorithms for computation requires effective
 hardware architectures that can achieve maximum performance with reduced power dissipation. Our project discusses the design and implementation of an efficient neural network
 accelerator hardware architecture with a systolic array of 4×4 for the matrix multiplication
 operation. The architecture employs parallel Processing Elements (PEs) to perform multiply-
accumulate (MAC) operations with pipelined execution, improving throughput. A BRAM based memory system is used to enable controlled data feeding and reduce I/O overhead. To
 enhance power efficiency, sparse-aware computation is implemented to skip zero operations which reduce switching activity. Simulation results confirm
 correct functionality with computation completed in 10 clock cycles. Power analysis shows
 a reduction of approximately 26% in dynamic power and 11% in total power, while BRAM
 usage reduces I/O utilization from 754% to 42%. The proposed design achieves an effective
balance between performance, power efficiency and resource utilization.
