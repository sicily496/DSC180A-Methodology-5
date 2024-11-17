**Zhiqing Wang**  
*zhw055@ucsd.edu*  

**A15 - Rayan Saab and Alex Cloninger**  

---

### 1. What is the most interesting topic covered in your domain this quarter?  

A particularly compelling topic discussed by other members of the section concerns whether compressed models exhibit generalization across subsets of categories. Additionally, it explores whether these models perform differently depending on the category, raising important questions about model robustness and transferability.  

---

### 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project  

One topic I am keen to explore is the application of low-rank factorization to the weights of a neural network, followed by iterative refinement of these parameters using a greedy path-following approach. During group discussions, we also identified two additional research directions:  

- **Error bounds for knowledge distillation methods:** Can we develop theoretical bounds to evaluate the reliability and limitations of these methods?  
- **Synergistic effects of combining knowledge distillation with other techniques:** Specifically, what happens when we integrate knowledge distillation with methods like the Neural Tangent Kernel (NTK) or low-rank factorization? Could this combination yield similar performance while achieving greater compression?  

---

### 3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?  

Initially, our project aimed to apply the greedy path-following approach to the MNIST dataset. However, after discussions with our mentor, we recognized that MNIST's classification task is overly simplistic for neural networks. Consequently, we shifted to using CIFAR-10, a dataset that, while also comprising 10 categories, includes more complex images such as airplanes and cats. This change provides greater challenges and opportunities for model compression.  

Additionally, rather than training a custom neural network, we plan to leverage existing architectures like ResNet. Our focus will then shift to optimizing the parameters for compression within these established models.  

---

### 4. What other techniques would you be interested in using in your project?  

Through discussions with group members, I have become interested in exploring the Neural Tangent Kernel (NTK) as a quantification method. NTK operates under the principle that gradient descent in a neural network with infinite width is equivalent to kernel gradient descent using NTK. This method has potential for improving the theoretical underpinnings of our Quarter 2 project.  
