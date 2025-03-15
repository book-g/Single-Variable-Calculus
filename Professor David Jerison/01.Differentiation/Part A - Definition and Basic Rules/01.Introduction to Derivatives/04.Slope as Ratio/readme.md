## **Slope as a Ratio**  

Now that we have a **geometric** understanding, let’s introduce **symbols and formulas** to compute derivatives.  

### **Secant Line & Slope Calculation**  
Consider a function \( f(x) \) and a point:  
\[
P = (x_0, f(x_0))
\]  
Move **horizontally** by a small amount \( \Delta x \) (called **"delta x"**, or **"the change in x"**), reaching a new point:  
\[
Q = (x_0 + \Delta x, f(x_0 + \Delta x))
\]  
These two points define a **secant line** on the graph of \( f(x) \).  

### **Finding the Secant Line Slope**  
The **vertical difference** (change in function value) between \( P \) and \( Q \) is:  
\[
\Delta f = f(x_0 + \Delta x) - f(x_0)
\]  
The **slope of the secant line** is given by the ratio of rise to run:  
\[
m_{\text{secant}} = \frac{\Delta f}{\Delta x} = \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
\]  

### **Limit Definition of the Derivative**  
Since the **tangent line is the limit of secant lines**, the **slope of the tangent line** is the **limit of secant slopes** as \( Q \to P \) (or as \( \Delta x \to 0 \)):  
\[
m = \lim_{\Delta x \to 0} \frac{\Delta f}{\Delta x} = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
\]  
This limit is called the **derivative** of \( f(x) \) at \( x_0 \), denoted as:  
\[
f'(x_0) = \lim_{\Delta x \to 0} \frac{f(x_0 + \Delta x) - f(x_0)}{\Delta x}
\]  

### **Key Takeaways**  
✅ The **secant line slope** is the average rate of change between two points.  
✅ The **tangent line slope** is the **instantaneous rate of change**, found as the **limit of secant slopes**.  
✅ The **derivative** \( f'(x_0) \) gives the slope of the function at \( x_0 \).  

---

📌 **MIT OpenCourseWare**  
🔗 [MIT OCW – 18.01SC Single Variable Calculus](http://ocw.mit.edu)  
📅 **Fall 2010**  
📜 For citation and terms of use: [MIT OCW Terms](http://ocw.mit.edu/terms)  