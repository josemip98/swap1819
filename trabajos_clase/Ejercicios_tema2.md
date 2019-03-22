# EJERCICIOS TEMA 2 

## Ejercicio T2.1: 
 
** Calcular la disponibilidad del sistema si tenemos dos réplicas de cada elemento (en total 3 elementos en cada subsistema). **

As = Acn-1 + ( (1 – Acn-1) * Acn)

web2=85% + ((1-85%)*85%)=97.75%
web3=97.75% + ((1-97.75%)*85%)=99.6625%

application2=90% + ((1-90%)*90%)=99%
application3=99% + ((1-99%)*90%)=99.9%

DB2=99.9% + ((1-99.9%)*99.9%)=99.9999%
DB3=99.9999% + (1-99.9999%)*99.9%)=99.9999999%

DNS2=98% + ((1-98%)*98%)=99.96%
DNS3=99.96% + ((1-99.96%)*98%)=99.9992%

Firewall2=85% + ((1-85%)*85%)=97.75%
Firewall3=97.75% + ((1-97.75%)*85%)=99.6625%

Switch2=99% + ((1-99%)*99%)=99.99%
Switch3=99.99% + ((1-99.99%)*99%=99.9999%

DC2=99.99% + ((1-99.99%)*99.99%)=99.999999%
DC3=99.999999% + ((1-99.999999%)*99.99%)=99.9999999999%

ISP2=95% + ((1-95%)*95%)=99.75%
ISP3=99.75% + ((1-99.75%)*95%)=99.9875%

AS=99.6625%*99.9%*99.9999999%*99.9992%*99.6625%*99.9999%*99.9999999999%*99.9875%=99.2135165%