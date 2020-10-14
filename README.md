# Runge-Kutta-4-SIRS-model-in-C
Example of an integration method for a system of ordinary differential equations.

I know, maybe now is not the right period to talk about epidemics but anyway...

In this case we integrate the SIRS model, a non-linear system of 3 differential equations that describes an epidemic with the hypotesis of non-mortal virus. With this hypotesis the N° of people is constant and we can describe the problem with only 2 ODE's.

In the code there is a force function that can be used add one or more time-dependent terms.

There are 3 main parameters: healthy, ill and resistant people.
