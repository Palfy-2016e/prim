# prim
Döntsük el egy számról, hogy prím-e! Írjunk függvényt
def primszam(num):
    if num < 2:
        return False
    if num == 2:
        return True
    else:
        for div in range(2,num):
            if num % div == 0:
                return False
        return True
