
% Equation Solve

%input Section
syms x y
eq1=input("Enter the first equation");
eq2=input("Enter the second equation");

%Formula section
sol=solve([eq1,eq2],[x,y]);
disp(sol.x);
disp(sol.y);
