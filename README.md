# Model Serving
Interesting articles, PoCs for model serving - from small, large to multiple servers. Multiple 



## Challenges in Serving
1. Multi-model serving
    1. Serving multiple frameworks
    2. Serving multiple models instances
2. Large model serving
    1. Tensor Parallel
    2. Pipeline Parallel
3. Logging
4. Metrics Measurements
   1. GPU Metrics
   2. CPU metrics
5. Micro-batching/Request management
   1. How to batch requests
   2. Timewindow for batches, number of requests on batches
6. Serving multiple protocols
   1. Protobuff/json etc.
   2. Http/Websocket/gRPC
7. Integration with Multiple types of model repos
   1. SFTP/FTP/S3/Object stores/Ceph/file system/HDFS
   
## Other Aspects

1. Model Pruning
2. Model Quantization
   a. Quantization pipeline (pre-deployments)
   b. Quantization aware training

## Secondary Aspects

1. REST Frameworks - FastAPI
2. Serving on Spark/Beam/Flink
3. 

## Interesting Frameworks
1. [Microsot fastformers](https://github.com/microsoft/fastformers)
2. [Nvidia's FasterTransformers](https://github.com/NVIDIA/FasterTransformer)
3. [DLJServing](https://github.com/deepjavalibrary/djl-serving)


## Good Articles
1. [Challenges on Model Deployment](https://neptune.ai/blog/model-deployment-challenges-lessons-from-ml-engineers)
2. [Parallel Tensor on AWS](https://aws.amazon.com/blogs/machine-learning/deploy-large-models-on-amazon-sagemaker-using-djlserving-and-deepspeed-model-parallel-inference/)
3. [Deep Speed's Inferencing](https://www.deepspeed.ai/tutorials/inference-tutorial/)
4. [DeepSpeed's Tutorial](https://github.com/microsoft/DeepSpeed/blob/master/docs/_tutorials/inference-tutorial.md)
5. [Large scale model inferecing](https://www.microsoft.com/en-us/research/blog/deepspeed-accelerating-large-scale-model-inference-and-training-via-system-optimizations-and-compression/)
