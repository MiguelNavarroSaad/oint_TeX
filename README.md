# Símbolos para integrales de contorno con dirección en TeX

Colocar los archivos CMEXC10.PK y CMEXC10.TFM en la carpeta del archivo .TEX  
y definir \ointi (dirección hacia la izquierda) y \ointd (dirección hacia la derecha)

``` 
\font\intcd=cmexc10
\textfont4=\intcd \scriptfont4=\intcd \scriptscriptfont4=\intcd
\mathchardef\ointiop="1448 \def\ointi{\ointiop\nolimits}
\mathchardef\ointdop="1452 \def\ointd{\ointdop\nolimits}
```

Se incluye .PDF con la explicación.
