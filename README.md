# -Implementing-Black-Box-Attacks-with-Transferable-Targeted-Perturbations
In adversarial machine learning, the transferability of targeted perturbations has long presented difficulties.
especially when it comes to black-box attacks, where creating
efficient perturbations is challenging due to the lack of access
to the internal workings of the target model. This study introduces a generative framework aimed at producing targeted
perturbations with high transferability across different machinelearning models. The framework captures both local and global
distributions of source and target images, guiding the generation
of adversarial perturbations. By analysing pixel distributions,
the model minimises the risk of boundary class swapping and
effectively generates targeted perturbations to fool the model into
misclassifying the inputs. The proposed architecture effectively
executed a black-box attack on ResNet-9 and ResNet-50 models,
significantly reducing their accuracies on the MNIST dataset. The
accuracy of ResNet-9 dropped from 99.57% to 18.75%, while
ResNet-50’s accuracy decreased from 99.14% to 39.89%. These
results highlight the superiority of the proposed architecture in
generating transferrable targeted perturbations.
