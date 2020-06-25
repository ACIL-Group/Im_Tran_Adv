# Impro_Trans_Adv_Ex
Project on improving the transferability of adversarial examples

Adversarial examples are created by imposing human-imperceptible noises on legitimate images purposefully, which can incur erroneous predictions from state-of-the-art image classifiers. Adversarial examples have the property of transfering from one model to another, the model which is used to create adversarial examples, is called the source model, the other model which the adversary want to fool, is called the target model. However, adversarial examples have the overfitting issue, which means that they often fool target model in a much lower success rate than the source model.
Unfortunately, the malicious images synthesized are prone to overfit to the exclusiveblind spots of the source model, although the crafted adversarial samples can attack thesource model with near 100% success rates, they suffer from limited success against thetarget model.

Some useful reference:
1. [Boosting Adversarial Attacks with Momentum, CVPR 2018](https://arxiv.org/pdf/1710.06081.pdf)
2. [Improving Transferability of Adversarial Examples with Input Diversity, CVPR 2019](https://arxiv.org/pdf/1803.06978.pdf)
3. [Evading Defenses to Transferable Adversarial Examples by Translation-Invariant Attacks, CVPR 2019](https://arxiv.org/pdf/1904.02884.pdf)
4. [Boosting the Transferability of Adversarial Samples via Attention, CVPR 2020](http://openaccess.thecvf.com/content_CVPR_2020/papers/Wu_Boosting_the_Transferability_of_Adversarial_Samples_via_Attention_CVPR_2020_paper.pdf)
