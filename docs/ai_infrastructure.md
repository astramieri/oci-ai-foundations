# AI Infrastructure

OCI AI Infrastructure is mainly composed of:
- GPU based instances: they can be virtual machines or bare metal machines. 
- High performance cluster networking: it allows instances to communicate to each other
- Super clusters: they are a massive network of GPU instances with multiple petabytes per second of bandwidth.
- Fully managed storage: from a single byte to exabytes without upfront provisioning are also available.

## GPU Architecture

ML and AI needs lots of repetitive computations to be made on huge amounts of data. Parallel computing on GPUs is designed for many processes at the same time. A GPU is a piece of hardware that is incredibly good in performing computations.

GPU has thousands of lightweight cores, all working on their share of data in parallel. This gives them the ability to crunch through extremely large data set at tremendous speed.

GPU instances are ideally suited for model training and inference.

## RDMA

RDMA is essentially, in a nutshell, is a technology that allows for data transfer or network communication that bypasses CPU, goes from one machine to another without any CPU interference. And this allows things like GPUs to communicate at extremely low latency, high bandwidth with low overhead from a CPU perspective. 