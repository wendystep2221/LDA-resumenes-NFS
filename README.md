# LDA-resumenes-NFS

<h2 style="color:#00CED1;" align="left"> Problema </h2> 

Desarrollar un modelo no supervisado que clasifique los resúmenes dentro de un tema específico, es decir, agrupar los resúmenes basado en su similitud semántica.

<h2 style="color:#00CED1;" align="left"> Metodología propuesta </h2> 

Se propone para la solución de este problema un modelo de **Asignación Latente de Dirichlet** o **LDA** por sus siglas en inglés. Este modelo asocia tópicos a cada documento (en nuestro caso résumenes de artículos de investigación
que fueron extraídos por la Fundación Nacional de Ciencia) de acuerdo a las palabras contenidas en cada uno. Cada tópico tiene una medida de aporte entre 0 y 1 al documento (probabilidad), siendo posible extraer el tópico que más aporta o se ajusta para así crear grupos especificos.

**NOTA: El resultado del estudio arrojó 14 grupos, adjunto se encuentra un archivo de tipo pickle(.pkl) que contiene la asignación de acuerdo al ID de cada articulo: "df_topics.pkl" , Adicional a ello se puede visualizar cada tópico en el documento "LDA-14-topics.html"**
