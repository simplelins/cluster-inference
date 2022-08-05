# cluster-inference
For safety concern, we have to build a reliable communication architecture to ensure that the service is correctly initialized in the cloud and not modified and the secure point-to-point channel is built between user and Secure MLaaS. The architecture of communication is proposed as follows:

![avatar](activity-graph.png)


## Port distribution
| Name        | ip    |  port(communication\|attestation)  |
| --------   | -----:   | :----: |
| Slave        |    IP   |   22100---, 32100---    |
| scheduler        |   IP    |   22000, 32000   |
| Overlay        |   IP    |   21000---, 31000---    |
