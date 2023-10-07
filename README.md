# pandas_problems.py
import pandas as pd
ch=[chr(i) for i in range (97,123)]
eng=pd.Series(ch)
print(eng)


#vovels ,having 5 elements with index 
#labels a e io u  and all the five values set to zero  .
raj=pd.Series([2,4,6,8,10],index=["a","e","i","o","u"])
raj[:]=0
print(raj)
