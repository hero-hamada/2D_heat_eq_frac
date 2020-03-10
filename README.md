# 2D_puasson_jacobi
2d puasson eq with jacobi method

(∂^2 u)/(∂x^2 )+(∂^2 u)/(∂y^2 )=-f(x,y)
  u_x (0,y)=y,     u_x (1,y)=ycos(y)
u(x,0)=0,     u(x,1)=sin⁡(x)
   f(x,y)=sin⁡(xy)(x^2+y^2)
u_ij^(n+1)=1/4 (u_(ij-1)^n+u_(ij+1)^n+u_(i-1j)^n+u_(i+1j)^n+f_ij h^2 ),   0<i<N,   0<j<M   
