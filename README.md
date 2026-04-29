# balance_car_rl
Practical Reinforcement Learning Implementation of STM32 Self-Balancing Vehicle Based on Neural Networks
This project is a further research outcome based on the STM32 self-balancing robot designed by Bilibili creator "会飞的鱿鱼 03". A neural network with a structure of 7×16×16×2 is adopted.
Due to the limited performance of the STM32F103C8T6, large-scale neural networks cannot be applied. Otherwise, excessive time will be consumed for inference, resulting in control latency and failure of balance maintenance.
For better performance, it is recommended to use chips such as the STM32F411CEU6 and higher-specification models. I am currently experimenting with deploying larger neural networks on this chip.
