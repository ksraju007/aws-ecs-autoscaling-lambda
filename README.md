# aws-ecs-autoscaling-lambda
cloudwatch alarm triggered lambda function to autoscale ECS services

Setup an alarm in cloudwatch for any metric combination you like.

Then deploy the stack, provide the parameters.

When the alarm is OK, it will scale down the service, when it is not OK, it will scale up the service.

To protect the cost, there is a upper and lower limit provided.

Rest if self-explanatory.
