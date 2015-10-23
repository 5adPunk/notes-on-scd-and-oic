# notes-on-scd-and-oic
## here i will:

work on my project at home and at work.

## here is my code so far for my project:

```python x = input('Enter the aluminium fraction as a decimal ')
x = float(x)
def algaasbg(x):
    return 1.439 + (1.042*x) + (0.468*x*x)
shortAns= format(algaasbg(x),'.4g')
print ('The bandgap for this fraction is,', shortAns,'eV')


'''Energy separation (EΓ) between Γ and top of valence band'''	
def eSepRV(x):    
    return 1.424 + 1.155*x + 0.37*x*x #eV
prettyRV = format(eSepRV(x),'.4g')
print ('The E sep R to VB for this fraction is,', prettyRV,'eV')

#Energy separation (EX) between X-valley and top of valence band	1.9+0.124x+0.144x2 eV
#Energy separation (EL) between L-valley and top of valence band	1.71+0.69x eV

def eSepXV(x):    
    return 1.9 + 0.124*x + 0.144*x*x #eV
prettyXV = format(eSepXV(x),'.4g')
print ('The E sep for X to VB for this fraction is,', prettyXV,'eV')


def eSepLV(x):    
    return 1.71 + 0.69*x #eV
prettyLV = format(eSepLV(x),'.4g')
print ('The E sep for L to VB for this fraction is,', prettyLV,'eV')
```
