```python
lib = {"noun":["世界冠军","我","鼓励","喜之郎","太空人","爷爷","奶奶","爷爷奶奶","喜之郎果冻"],"verb":["长大","当","给","吃"],"adj":["高兴","爱"],"adv":["要","可"]}
a = 0
for i1 in lib["verb"] :
    for i2 in lib["noun"] :
        for i3 in lib["adv"] :
            for i4 in lib["verb"] :
                for i5 in lib["noun"] :
                    a += 1
                    print("1."+str(a)+":"+i1+i2+i3+i4+i5)
a = 0
for i1 in lib["noun"] :
    for i2 in lib["verb"] :
        for i3 in lib ["noun"] :
            for i4 in lib ["noun"] :
                for i5 in lib["noun"] :
                    a += 1
                    print("2."+str(a)+":"+i1+i2+i3+i4+"和"+i5)
a = 0
for i1 in lib["noun"] :
    for i2 in lib["adv"] :
        for i3 in lib["verb"] :
            for i4 in lib["noun"] :
                a += 1
                print("3."+str(a)+":"+i1+i2+i3+i4+i5)
a = 0
for i1 in lib["noun"] :
    for i2 in lib["adv"] :
        for i3 in lib["adj"] :
            a += 1
            print("4."+str(a)+":"+i1+i2+i3+"了")
a = 0
for i1 in lib["verb"] :
    for i2 in lib["noun"] :
        for i3 in lib["adj"] :
            for i4 in lib["verb"] :
                for i5 in lib["noun"] :
                    a += 1
                    print("5."+str(a)+":"+i1+i2+i3+i4+"的"+i5)
```
