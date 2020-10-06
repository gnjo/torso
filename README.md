# torso
torso is like a wizardry engine
```
/m/ //img sound bgm 
torso.js //macro engine
torso.css
santique.otf
three.js
movebox.js
dungbuild.js //
lab.js //random dungeron 
//ui
hud.js
planes.js
//
val.js //global value&fn
view.js
main.js
//macro
data.txt //or .csv
start.txt
```

```
//fn.js

dice('2d3+5')
dice(2,3,5)
ac2r() //armor class to percent

dice('2d3t2c20+5') //dice check
dice('2d3t2+5',-9) //damage
dice('2c50') //1d100t2c50 



hit rate
11 100
10 99
9 95
8 90
7 85
6 80
5 75
4 70
3 65
2 60
1 55
0 50
-1 45
-2 40
-3 35
-4 30
-5 25
-6 20
-7 15
-8 10
-9 5
-10 4
-11 3
-12 2
-13 1
-14 1

function ac2rate(ac){
 if(ac===void 0)return 100
 if(ac>10)return 100
 if(ac===10)return 99
 if(ac<-12)return 1
 if(ac===-10)return 4
 if(ac===-11)return 3
 if(ac===-12)return 2
 return (ac+10)*5
}


```

```
ダンジョンに関して。
スタンディングオブジェクトは、アイコンを回転させ、その足元に来た時に、二次元的に表示させる。



```


