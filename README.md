clear;
clc;
delta=1/100;//Relative refractive difference index
n1=1.46;//core refractive index (assumption）

NA=n1*sqrt(2*delta);//computing numerical aperture
theta=1-delta;
Critical_angle=asind(theta);//computing critical angle
printf('\nNumerical aperture is %.2f\n Critical angle is %.If degree.',NA,Critical_angle);
--->
