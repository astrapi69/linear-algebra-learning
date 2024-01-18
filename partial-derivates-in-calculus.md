# Partial Derivatives in Calculus

## 1. Derivative of a Function with One Variable:
   - Example: \( f(x) = x^2 \)
     - Derivative: \( f'(x) = 2x \)
     - If \( x = 3 \), then \( f'(3) = 2 \times 3 = 6 \). This means that for every unit increase in \( x \) around \( x = 3 \), \( f(x) \) increases by approximately 6.

## 2. Partial Derivative of a Function with Two Variables:
   - Example: \( f(x, y) = x^2 + y^2 \)
     - Partial derivative with respect to \( x \): \( \frac{\partial f}{\partial x} = 2x \)
       - If \( x = 3 \) and \( y = 4 \), then \( \frac{\partial f}{\partial x} = 2 \times 3 = 6 \). This means that for a small change in \( x \) around \( x = 3 \), \( f \) changes approximately 6 times that amount.
     - Partial derivative with respect to \( y \): \( \frac{\partial f}{\partial y} = 2y \)
       - If \( x = 3 \) and \( y = 4 \), then \( \frac{\partial f}{\partial y} = 2 \times 4 = 8 \). This means that for a small change in \( y \) around \( y = 4 \), \( f \) changes approximately 8 times that amount.

## 3. Interpretation:
   - Continuing with the previous example, if \( x = 3 \) and \( y = 4 \), \( \frac{\partial f}{\partial x} \) at that point is 6, indicating the sensitivity of \( f \) to changes in \( x \) at that specific point.

## 4. Notation:
   - Using the same example, \( \frac{\partial}{\partial x}(x^2 + y^2) = 2x \) and \( \frac{\partial}{\partial y}(x^2 + y^2) = 2y \).

## 5. Higher-Order Partial Derivatives:
   - Example: \( f(x, y) = x^3 + 3xy^2 \)
     - Second partial derivative with respect to \( x \): \( \frac{\partial^2 f}{\partial x^2} = 6x \)
       - If \( x = 2 \), then \( \frac{\partial^2 f}{\partial x^2} = 6 \times 2 = 12 \). This represents how the rate of change of \( f \) with respect to \( x \) changes as \( x \) varies, while \( y \) is held constant.

## 6. Chain Rule for Partial Derivatives:
   - Consider a function \( g(u, v) \) where \( u = x^2 \) and \( v = y^2 \). Now, let's define \( f(g(u, v)) = u + v \).
     - The chain rule for partial derivatives states that \( \frac{\partial f}{\partial x} = \frac{\partial f}{\partial u} \cdot \frac{\partial g}{\partial x} + \frac{\partial f}{\partial v} \cdot \frac{\partial g}{\partial y} \).
     - If \( x = 2 \), \( y = 3 \), then \( \frac{\partial f}{\partial x} = 2 \cdot 2x + 1 \cdot 0 = 4x \). If \( x = 2 \), this evaluates to \( 4 \times 2 = 8 \), representing the rate of change of \( f \) with respect to \( x \) considering the chain rule.
