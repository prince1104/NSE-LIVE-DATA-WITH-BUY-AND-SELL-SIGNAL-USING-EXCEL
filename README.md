# NSE LIVE DATA WITH BUY AND SELL SIGNAL :-

## EXCEL FORMULAS USED :-

### LOW% :- =+([@LOW]-[@OPEN])/[@OPEN]*100
### HIGH% ;- =+([@High]-[@open])/[@open]*100
### LTP% :- =+([@LTP]-[@open])/[@open]*100
### SIGNAL :- =+IF([@[LOW%]]=0,"BUY+",IF([@[HIGH%]]=0,"SELL+",IF(AND([@[LTP%]]>0,[@[LOW%]]>-0.5),"BUY",IF(AND([@[LTP%]]<0,[@[HIGH%]]<0.5),"SELL",IF([@[LTP%]]>0,"B",IF([@[LTP%]]<0,"S",""))))))
## GAP% ; =+([@open]-[@Close])/[@Close]*100

![gggggg](https://user-images.githubusercontent.com/48179170/130896978-6a271e4f-f9d4-4434-ae95-070fc2cdd7db.png)
