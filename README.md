# wd-asssembly
Exécuter de l'**assembleur** en **WLangage** / Execute **assembly** code in **WLangage**

exemple :
```javascript
sCodeAsm est chaîne  = [
```
```Assembly
	mov	 EAX,1234
	push ebp
	mov  ebp,esp
	pop  ebp 
	ret  8
```
```javascript
]
maProcAssembleur est une Procédure = compileAsmX86( sCodeAsm )
Trace( maProcAssembleur( x ) )
```

Le code source est au format *texte* WinDev 25.

