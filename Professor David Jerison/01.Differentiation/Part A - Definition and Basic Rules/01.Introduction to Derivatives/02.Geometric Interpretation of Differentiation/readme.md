## **Geometric Interpretation of Differentiation**  


![](figure1)


This image visually represents the **geometric interpretation of differentiation** by showing:  

- **The function** \( f(x) \) as a curved black line.  
- **Point \( P \) at \( (x_0, f(x_0)) \)**, where the derivative is evaluated.  
- **Point \( Q \) at \( (x_0 + \Delta x, f(x_0 + \Delta x)) \)**.  
- **The secant line (green, dashed)** connecting \( P \) and \( Q \), representing the average rate of change.  
- **The tangent line (red, solid)** at \( P \), which represents the instantaneous rate of change (the derivative).  

As \( Q \) moves closer to \( P \) (i.e., as \( \Delta x \to 0 \)), the **secant line approaches the tangent line**, and its slope approaches the **derivative** \( f'(x_0) \).



### **Tangent Line & Secant Line**  

The **derivative** of a function \( f(x) \) at \( x = x_0 \) represents the **slope of the tangent line** to the graph of \( f(x) \) at the point \( (x_0, f(x_0)) \).  

But what exactly is a **tangent line**?  
- **It is NOT** just a line that touches the graph at one point.  
- It is the **limit** of the secant lines that pass through the points:  
  - **\( P = (x_0, f(x_0)) \)**
  - **\( Q = (x_0 + \Delta x, f(x_0 + \Delta x)) \)**  
  as \( Q \) approaches \( P \).  

### **Key Properties of the Tangent Line**  
✅ It touches the graph at \( (x_0, f(x_0)) \).  
✅ Its **slope** matches the **direction** of the graph at that point.  
✅ It is the **best linear approximation** to the graph at \( x_0 \).  

### **Computing the Equation of the Tangent Line**  
Given a function \( f(x) \), how do we find the equation of the **tangent line** at a point \( P = (x_0, y_0) \)?  

#### **General Equation of a Straight Line**  
A line with slope \( m \) passing through a point \( (x_0, y_0) \) is given by:  
\[
y - y_0 = m(x - x_0)
\]  

#### **Steps to Find the Tangent Line**  
1️⃣ Identify \( x_0 \), the point where the tangent line touches the curve.  
2️⃣ Compute \( y_0 \) by evaluating \( f(x_0) \), i.e., \( y_0 = f(x_0) \).  
3️⃣ Find the **slope** of the tangent line:  
   \[
   m = f'(x_0)
   \]  
4️⃣ Substitute \( x_0, y_0, \) and \( m \) into the line equation:  
   \[
   y - f(x_0) = f'(x_0)(x - x_0)
   \]  

### **Definition of the Derivative**  
The **derivative** of \( f(x) \) at \( x_0 \), written as \( f'(x_0) \), is **the slope of the tangent line** to \( y = f(x) \) at the point \( P = (x_0, f(x_0)) \).  

---

📌 **MIT OpenCourseWare**  
🔗 [MIT OCW – 18.01SC Single Variable Calculus](http://ocw.mit.edu)  
📅 **Fall 2010**  
📜 For citation and terms of use: [MIT OCW Terms](http://ocw.mit.edu/terms)  