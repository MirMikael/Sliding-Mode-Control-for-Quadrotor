Certainly! Here are the sliding surfaces expressed in mathematical notation:

1. **\( S_{i} \)**:
\[ S_{i}= \dot{e} + \lambda_{i} \cdot e \]
\[ \dot{S}= k \tanh (S)\]
2. **\( S_{\theta} \)**:
\[ S_{\theta}[i+1] = \dot{x}_{1d} - x_4[i] + \lambda_1 \cdot (x_{1d} - x_3[i]) \]

3. **\( S_{\psi} \)**:
\[ S_{\psi}[i+1] = \dot{x}_{1d} - x_6[i] + \lambda_2 \cdot (x_{1d} - x_5[i]) \]

4. **\( S_{z} \)**:
\[ S_{z}[i+1] = \dot{x}_{1d} - x_{12}[i] + \lambda_3 \cdot (z_d - x_{11}[i]) \]

5. **\( S_{x} \)**:
\[ S_{x}[i+1] = -x_8[i] + \lambda_4 \cdot (x_d - x_7[i]) \]

6. **\( S_{y} \)**:
\[ S_{y}[i+1] = -x_{10}[i] + \lambda_5 \cdot (y_d - x_9[i]) \]

Where:
- \( \dot{x}_{1d} \) is the desired derivative of the first state variable.
- \( x_i[i] \) (for \( i = 1, 2, ..., 12 \)) represents the value of the \( i \)th state variable at time step \( i \).
- \( x_{1d} \), \( x_d \), and \( y_d \) are desired values for the first, fifth, and sixth state variables, respectively.
- \( z_d \) is the desired value for the altitude (the twelfth state variable).
- \( \lambda_0, \lambda_1, ..., \lambda_5 \) are control gains corresponding to each sliding surface.

These equations capture the deviation between the desired and actual values of the state variables, weighted by the control gains. The sliding mode control adjusts the control inputs based on these sliding surfaces to drive them to zero, thereby stabilizing the system and achieving desired trajectory tracking.
