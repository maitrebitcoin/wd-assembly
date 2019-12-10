# wd-asssembly
Exécuter de l'**assembleur** en **WLangage** / Execute **assembly** code in **WLangage**

# exemple
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

# asm supportés
- intel x86 32 bits
- intel x86 64 bits

# détail
Le code source est au format **texte** WinDev 25.
Il faut avoir WinDev 25 installé pour pouvoir le compiler.
Il génère un composant externe qui peut ensuite être utilisé dans tout projet *WinDev* ou *WebDev*.
