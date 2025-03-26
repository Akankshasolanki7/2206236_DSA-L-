# Simple Linear Regression using Gradient Descent  

## Overview  
In this assignment, we implement a **Simple Linear Regression Model** using the **Gradient Descent Algorithm**. The goal is to fit a straight line to a given dataset and analyze the behavior of the cost function under different learning rates and optimization methods.  

---

## **Tasks & Questions**  

### **1. Implement Linear Regression with Gradient Descent**
- Fit a straight line to the given dataset using **linear regression**.  
- Set the **learning rate (lr) to 0.5**.  
- Report the **final cost function value** and the **optimized parameters (weights & bias)** after convergence.  
- Mention the **convergence criteria** used in your implementation.  

### **2. Understanding the Cost Function**
- The cost function used in this assignment differs from the one covered in class.  
- What are the advantages of **averaging the cost function** instead of summing it?  

### **3. Plot Cost Function vs Iterations**
- Generate a graph showing the **cost function vs iteration** for the first **50 iterations**.  

### **4. Visualizing the Model**
- Plot the **given dataset**.  
- Overlay the **best-fit line** obtained from your model to visualize how well it fits the data.  

### **5. Effect of Learning Rate on Convergence**
- Test your model with different learning rates:  
  - **lr = 0.005**  
  - **lr = 0.5**  
  - **lr = 5**  
- For each learning rate:  
  - Plot a graph showing **how the cost function changes** over the first **50 iterations**.  
  - Record your **observations** on the effect of different learning rates.  

### **6. Implement Different Gradient Descent Techniques**
- Choose a **suitable learning rate** and compare:  
  - **Batch Gradient Descent (BGD)**  
  - **Stochastic Gradient Descent (SGD)**  
  - **Mini-Batch Gradient Descent (MBGD)**  
- Plot the **cost function vs iteration** for each method.  
- Compare how the cost function behavior changes across these methods.  

---

## **How to Run the Code**
1. Clone this repository:  
   ```bash
   git clone <repo-url>
   cd <repo-folder>

