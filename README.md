# Free-trial-gym
def freeTrial(tsampatzides,lista,name):
    if name in lista:
        print ("you have already tried free trial dear "+name)
        tsampatzides.append(name)

    else:
        lista.append(name)
        print("welcome back "+name)

lista = []
tsampatzides = []
while len(lista)<4:
    name = input("give me a name ")
    freeTrial(tsampatzides,lista,name)
print(lista)
print(tsampatzides)
