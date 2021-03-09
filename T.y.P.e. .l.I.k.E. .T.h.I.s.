x = str(input())
evenLst = []
oddLst = []
for i in range(0, len(x), 2):
    evenLst.append(x[i])
for i in range(1, len(x), 2):
    oddLst.append(x[i])
y = ""
i=0
if len(evenLst)>len(oddLst):
    for i in range(0, len(oddLst)):
        y += evenLst[i].upper()+"."+oddLst[i].lower()+"."
        i += 1
    y += evenLst[len(evenLst) - 1].upper()+"."
    print(y)
elif len(evenLst) < len(oddLst):
    for i in range(0, len(evenLst)):
        y += evenLst[i].upper() + "." + oddLst[i].lower()+"."
        i += 1
    y += oddLst[len(oddLst)-1].lower()+"."
    print(y)
else:
    for i in range(0, len(evenLst)):
        y += evenLst[i].upper() + "." + oddLst[i].lower()+"."
        i += 1
    print(y)

