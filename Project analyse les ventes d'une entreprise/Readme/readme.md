

Librairie utilisée pour le script destiné à nettoyer le jeu de données ;
 
 IDE: Jupyter notebook
 
 Nettoyage dataframe : pandas , numpy
 Visualisation : matplotlib, seaborn 

 Agrandir cellule notebook :  from IPython.core.display import display, HTML
 display(HTML("<style>.container { width:100% !important; }</style>"))
 


Librairie utilisée pour le script contenant les différentes analyses effectuées et mission 3 Corrélation
 

 Agrandir cellule notebook :
 IPython.core.display import display, HTML
 display(HTML("<style>.container { width:100% !important; }</style>"))


 manipulation données: pandas numpy
 
 visualisation: matplotlib, seaborn
 
 Tests statistiques: Anova , chi2, corrélation 
 scipy
 scipy.stats import chi2_contingency
 scipy.stats import shapiro
 scipy.stats import pearsonr
 scipy.stats import f_oneway
 scipy.stats.kruskal
 
 Graphique qqplot
 statsmodels.graphics.gofplots import qqplot

 Calculer Eta carré: 
 pingouin 
 
 
 Régression linéaire:
 statsmodels.formula.api as smf
 statsmodels.api as sm
 statsmodels.formula.api import ols