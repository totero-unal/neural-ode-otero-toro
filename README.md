# Neural ODEs sobre Datos Biologicos
**Analisis Numerico | Universidad Nacional de Colombia**  
Prof. Carlos Manuel Orrego Franco  
Generado: 2026-05-24  

---

## Integrantes
- Tomas Otero Lopez
- Juan Esteban Toro Soto

## Dataset
**COVID-19 JHU (nuevos casos diarios)**  
- Trayectorias: 178  
- Pasos de tiempo: 400  
- Variables: Nuevos casos (norm.)  

## Resultados (100% de observaciones)
| Modelo | RMSE Rec | RMSE Ext | Params | Tiempo |
|--------|----------|----------|--------|--------|
| Metodo Clasico | 0.0000 | nan | 4 | 0.0s |
| Neural ODE | 0.4995 | nan | 4,897 | 2730.7s |
| Latent ODE | 0.6017 | nan | 9,281 | 3567.7s |

## Reproducir
```bash
# Abrir A_notebook_base.ipynb en Google Colab
# Ejecutar todas las celdas en orden desde la Seccion 1
```

## Estructura
```
notebooks/   <- NB01-NB07 + A_notebook_base.ipynb
informe/     <- informe.tex + informe.pdf
evidencia_ia/ <- capturas del chat con la IA
README.md
```
