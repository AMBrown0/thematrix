---
share: true
---
https://www.khanacademy.org/math/statistics-probability/describing-relationships-quantitative-data/more-on-regression/v/squared-error-of-regression-line

![linear_regression_first_prlps.pdf](./linear_regression_first_prlps.pdf)
[](.md)

![Pasted image 20230320151208](./Pasted%20image%2020230320151208.png)

![Pasted image 20230320151240](./Pasted%20image%2020230320151240.png)



$$(y_i - (b_0+b_{1}x_{1}))^2$$

$$(y_i - (b_0+b_{1}x_{1})).(y_i - (b_0+b_{1}x_{1}))$$   
$$y_{i}^2-y_{i}(b_{0}+b_{1}x_{1})-y_{1}(b_{0}+b_{1}x_{1})+(b_{0}+b_{1}x_{1})^2
$$
$$y_{i}^2-2(b_{0}+b_{1}x_{1})+(b_{0}+b_{1}x_{1})^2$$
![Pasted image 20230320161318](./Pasted%20image%2020230320161318.png)

![Pasted image 20230320162124](./Pasted%20image%2020230320162124.png)

Simplifies to 
![Pasted image 20230320162351](./Pasted%20image%2020230320162351.png)

This equation maps to a 3d plane we are looking to minimise SE
![Pasted image 20230320162838](./Pasted%20image%2020230320162838.png)

![Pasted image 20230320163038](./Pasted%20image%2020230320163038.png)
![Pasted image 20230320164404](./Pasted%20image%2020230320164404.png)
![Pasted image 20230320151534](./Pasted%20image%2020230320151534.png)






### Python to plot x,y,z m,b,SSE
![show_regression_error_v3.py](./show_regression_error_v3.py.md)



