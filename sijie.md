LSR
pointA = [ 1, 2,   0*pi/180 ];     
pointB = [ 5, 4,   15*pi/180 ];    
TurnRadius =3;   
PathStep = -2;   
dubins_curve(pointA,pointB, TurnRadius, PathStep);

RSL
pointA = [ 1,2,   -30*pi/180 ];     
pointB = [3,5,   70*pi/180 ];    
TurnRadius =3;   
PathStep = -2;   
dubins_curve(pointA,pointB, TurnRadius, PathStep);

LSL
pointA = [ 3,2,  0*pi/180 ];     
pointB = [3,5,  0*pi/180 ];    
TurnRadius =3;   
PathStep = -2;   
dubins_curve(pointA,pointB, TurnRadius, PathStep);

RSR
pointA = [ 3,6,  30*pi/180 ];     
pointB = [1,2,  60*pi/180 ];    
TurnRadius =3;   
PathStep = -2;   
dubins_curve(pointA,pointB, TurnRadius, PathStep);

RLR
pointA = [1,2, -30*pi/180 ];     
pointB = [3,5,  60*pi/180 ];    
TurnRadius =2;   
PathStep = -2;   
dubins_curve(pointA,pointB, TurnRadius, PathStep);

LRL
pointA = [1,2, 60*pi/180 ];     
pointB = [3,5,  -30*pi/180 ];    
TurnRadius =2;   
PathStep = -2;   
dubins_curve(pointA,pointB, TurnRadius, PathStep);