# Software code for
## APPLICATION OF LIMIT STATE FUNCTION METHOD TO STATISITCAL ANALYSIS OF BALLISTIC PENETRATION   
                                          Shinsuke SAKAI (Yokohama National University, Japan)   
###  Requirements
1. The procedures for using Jupyter must be completed   
1. Whenever a package is reported as missing, install it using the pip command in the terminal  

###  Procedure
1. Download all contents in this repository   
1. Move to the Downloads folder   
1. Execute the following program for BRL example in the Jupyter code window   
```python
import InterPenet as ip
bb=ip.Base()
bb.CalcPenet('BRL.pkl')
```
If the following is output, the system is operating correctly.   
```
**Validation of [ v_bl ] satisfied**
**Validation of [ Limp/d ] satisfied**
**Validation of [ b/d ] satisfied**
**Validation of [ Lsh/d ] satisfied**
**Validation of [ Su ] not satisfied**: ,Value= 490000000.0
*** Probabilistic analysis ***
[ BRL Formula ]
variable= ['b', 'd', 'm', 'v', 'Me']
beta= -0.5571767489022684
Alpha= [ 0.06413751  0.06413751 -0.0427838  -0.9006759   0.42275907]
Pf= 0.7112966629840962
*** Analysis of Balistic Limit Velocity ***
Vbl= 102.34312241793276
File= BRL.pkl
```