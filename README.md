I see! Let's correct that. Here's the revised text without LaTeX formatting:

---

**Sliding Mode Control (SMC)** is one of the most important nonlinear controllers.

### Sliding Surface:

For each state variable \( i \), the sliding surface \( S_i \) is defined as:

\[ S_i = \dot{e} + \lambda_{i} \cdot e \]

Where:
- \( \dot{e} \) is the derivative of the error.
- \( \lambda_{i} \) is the control gain for the \( i \)th state variable.
- \( e \) represents the error between the desired and actual values of the state variable.

### Switching Function:

The switching function \( \dot{S} \) is given by:

\[ \dot{S} = k \cdot \tanh(S) \]

Where:
- \( S \) is the sliding surface.
- \( k \) is the gain parameter.
- \( \tanh \) denotes the hyperbolic tangent function.

For the following state variables \( i \):
- \( i \) can take values of \( \phi, \theta, \psi, X, Y, Z \).

---

Now it should display correctly on GitHub. Let me know if you need further adjustments!
