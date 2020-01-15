# The-introduction-of-KDGAN
> Author: Wang Bowen (王博文)<br>
> Inspired by [【阅读笔记】KDGAN: Knowledge Distillation with Generative Adversarial Networks](https://blog.csdn.net/XD_Cauthy/article/details/89183685)<br>
> All rights reserved

## Related notion 
### Knowledge distillation  
#### Target  
>> Train a lightweight classifier suitable to provide accurate inference with constrained resources in multi-label learning <br>  

#### Bottleneck  
>> The accuracy of the classifier trained this way is usually suboptimal because it is difficult to learn the true data distribution from the teacher  

#### GAN  
>> An alternative method is to adversarially train the classifier against a discriminator in a two-player game akin to generative <br>  
>> adversarial networks (GAN), which can ensure the classifier to learn the true data distribution at the equilibrium of this game <br>  

## Idea of KDGAN 
>> we propose a three-player game named KDGAN consisting of a classifier, a teacher, and a discriminator <br>  
>> The classifier and the teacher learn from each other via distillation losses and are adversarially trained <br>  
>> against the discriminator via adversarial losses <br>  

## Architecture
![kdgan](/image/kdgan.bmp kdgan)

##  Methods
>> 
>> 