# Impro_Trans_Adv_Ex
Project on improving the transferability of adversarial examples

Adversarial examples are created by imposing human-imperceptible noises on legitimate images purposefully, which can incur erroneous predictions from state-of-the-art image classifiers. Adversarial examples have the property of transfering from one model to another, the model which is used to create adversarial examples, is called the source model, the other model which the adversary want to fool, is called the target model. However, adversarial examples have the overfitting issue, malicious images synthesized are prone to overfit to the exclusive blind spots of the source model, although the crafted adversarial samples can attack the source model with near 100% success rates, they suffer from limited success against the target model.

Steps for the project:

1. Get familiar with DNNs and the Imagenet dataset, test the accuracy of some typical pretrained models in tensorflow[https://github.com/tensorflow/models/tree/master/research/slim] or [pytorch](https://github.com/Cadene/pretrained-models.pytorch) on [NIPS 2017 Adversarial Attack Dataset](https://github.com/tensorflow/cleverhans/tree/master/examples/nips17_adversarial_competition/dataset).

2. Reproduce one of the papers below to get familiar to evaluate different attack and defense mothods, establish the framwork of the code for the project, leaving the module of generating adversarial examples changing.

3. Get inspiration from literature on how to alleviate overfitting, such as regularization, data augmentation, etc. This is more like a try and error process, if some methods help improve the transferability of adversarial examples, then we succeed.

Some useful reference:
1. [Boosting Adversarial Attacks with Momentum, CVPR 2018](https://arxiv.org/pdf/1710.06081.pdf)
2. [Improving Transferability of Adversarial Examples with Input Diversity, CVPR 2019](https://arxiv.org/pdf/1803.06978.pdf)
3. [Evading Defenses to Transferable Adversarial Examples by Translation-Invariant Attacks, CVPR 2019](https://arxiv.org/pdf/1904.02884.pdf)
4. [Boosting the Transferability of Adversarial Samples via Attention, CVPR 2020](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Boosting_the_Transferability_of_Adversarial_Samples_via_Attention_CVPR_2020_paper.pdf)
