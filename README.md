%i will be creating mathmatics function for matlab used 
%basic to professional to ML and AI..
%this function will be simple to used and navigate with
%function to calculate quadratic equation 

function quadratic = qua(a,b,c)
    %using quadrtic formular 
    d=b^2-4*a*c;   %
    x1=-b+sqrt(d)/2*a;
    x2=-b-sqrt(d)/2*a;
    %checked if the root is real number or complex
     quadratic=[x1,x2];
    if d>=0 
       fprintf('\tx1:%f\n\tx2:%f\n %.2f\n',quadratic);
    elseif d<=-1
        disp('complex');
     fprintf('\tx1:%f\n\tx2:%f\n %.2f\n',quadratic);
      
      end
end

%copy the code to your live script and save it as function mlx
%go to your command window and type qua(a,b,c) 
%Note a b c represent the coefficient of the qudratic equation 
