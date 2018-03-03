# Programlama-1-Odev-1
programlama 1 dersi ödevi
Soru 1
def gelirHesapla(x,y,z):
    gelir=(x+y+z)
    return gelir
x=int(input("Finansman gelirlerini giriniz:"))
y=int(input("Pazar gelirlerini giriniz::"))
z=int(input("Kira gelirlerini giriniz:"))
g=gelirHesapla(x,y,z)
print("Geliriniz:",g)
def giderHesaplama(a,b,c,d,e):
    gider=(a+b+c+d+e)
    return gider
a=int(input("Ücreti giriniz:"))
b=int(input("Finansman giderleri giriniz:"))
c=int(input("Pazar giderleri giriniz:"))
d=int(input("Kira giderlerini giriniz:"))
e=int(input("Muhasebe giderlerini giriniz:"))
gi=giderHesaplama(a,b,c,d,e)
print("Gideriniz:",gi)
def karHesaplama(g,gi):
    kar=(g-gi)
    return kar
k=karHesaplama(g,gi)
print("Karınız:",k)
if (g-gi)==1000:
    print("Ne kar ne de zarar ettiniz.")
elif (g-gi)>1000:
    print("Kar ettiniz.")
else:
    print("Zarar ettiniz.")
    
    Soru 2
    def kullanilabilirlikHesapla(x,y):
   kullanilabilirlik=((x-y)/x)
   return kullanilabilirlik
x=int(input("Planlanmış üretim süresini giriniz:"))
y=int(input("Plansız duruş giriniz:"))
k=kullanilabilirlikHesapla(x,y)
print("Kullanılabilirlik",k)
def performansHesaplama(a,b,x,y):
    performans=((a*b)%(x-y))
    return performans
a=int(input("Standart çevrim zamanını giriniz:"))
b=int(input("Üretim miktarını giriniz:"))
p=performansHesaplama(a,b,x,y)
print("Performansınız:",p)
def kaliteHesaplama(t,r):
    kalite=(t/r)
    return kalite
t=int(input("Sağlam ürün miktarını giriniz:"))
r=int(input("Toplam üretim miktarını giriniz:"))
ka=kaliteHesaplama(t,r)
print("Kaliteniz:",ka)
def oeeHesaplama(k,p,ka):
    oee=(k*p*ka)
    return oee
c=oeeHesaplama(k,p,ka)
print("Ekipman etkinlik oranınız:",c)

soru 3
def ciroHesapla(x,y):
    ciro=(x*y)
    return ciro
x=int(input("Satış miktarını giriniz:"))
y=int(input("Birim satış fiyatını giriniz:"))
c=ciroHesapla(x,y)
print("Cironuz:",c)
def adamBasiCiroHesapla(c,s):
    adamBasiCiro=(c/s)
    return adamBasiCiro
s=int(input("Toplam çalışan sayısını giriniz:"))
a=adamBasiCiroHesapla(c,s)
print("Adam başı cironuz:",a)
