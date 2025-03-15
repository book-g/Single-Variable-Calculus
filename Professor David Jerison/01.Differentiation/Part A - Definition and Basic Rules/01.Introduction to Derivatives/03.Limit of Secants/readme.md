## **Geometric Definition of the Derivative**  

We are still working toward a **computational method** to find the equation of the **tangent line**.  
But how do we compute its **slope** \( m \)?  
How do we determine which lines are **tangent lines** and which are not?  

### **Secant Line vs. Tangent Line**  
- A **secant line** connects two points on the graph of \( f(x) \).  
- If these points are **close together**, the **slope of the secant line** is **close to the slope of the curve** at that point.  
- The **goal** is to determine the slope of the **tangent line**, which represents the actual slope of the curve at a single point.  

### **Finding the Tangent Line Slope**  
1️⃣ Consider a **secant line** passing through points:  
   - \( P = (x_0, f(x_0)) \)  
   - \( Q = (x_0 + \Delta x, f(x_0 + \Delta x)) \)  
2️⃣ The **slope of the secant line** is given by:  
   \[
   m_{\text{secant}} = \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
   \]  
3️⃣ As \( Q \) moves closer to \( P \) (i.e., as \( \Delta x \to 0 \)), the **secant line approaches the tangent line**.  
4️⃣ The **tangent line slope** is the **limit** of secant line slopes:  
   \[
   m = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
   \]  
5️⃣ This limit is defined as the **derivative** of \( f(x) \) at \( x_0 \):  
   \[
   f'(x_0) = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
   \]  

Thus, the **tangent line is the limit of secant lines** as \( Q \) approaches \( P \).  

---

### **Key Differences from the Previous Explanation**  
🔹 The previous section introduced the **concept of the tangent line** and its role as the best linear approximation.  
🔹 This section focuses on the **computational method** for finding the tangent line using limits.  
🔹 The definition of the **derivative as a limit of secant slopes** is explicitly introduced here.  

---

📌 **MIT OpenCourseWare**  
🔗 [MIT OCW – 18.01SC Single Variable Calculus](http://ocw.mit.edu)  
📅 **Fall 2010**  
📜 For citation and terms of use: [MIT OCW Terms](http://ocw.mit.edu/terms)  