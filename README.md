# wd-asssembly
Exécuter de l'assembleur en **WLangage** / Execute assembly code in **WLangage**

# Exemple
```javascript
sCodeAsm est chaîne  = [
```
```Assembly
	mov	 EAX,1234
	push ebp
	pop  ebp 
	ret  8
```
```javascript
]
maProcAssembleur est une Procédure = compileAsmX86( sCodeAsm )
Trace( maProcAssembleur( x ) ) // affiche 1234 
```

# Asm supportés
- intel x86 32 bits
- intel x86 64 bits

# Détail
Le code source est au format *texte* **WINDEV 25**.
Il faut avoir **WINDEV 25** installé pour pouvoir le compiler.
Il génère un composant externe qui peut ensuite être utilisé dans tout projet **WINDEV** ou **WEBDEV**.
