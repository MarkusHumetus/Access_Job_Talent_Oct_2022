# Access_Job_Talent_Oct_2022
Project to access to the hackathon organised by Barcelona Digital Talen (17th October2022)

## Intro/Objectives: Introductory Project to Hackathon from IT&Decathlon 2022

Jorge es un geólogo del IGME (Instituto Geológico y Minero de España) que está desarrollando un nuevo sistema de prevención de erupciones para poder predecir qué tipo de erupción tendrá un volcán según las las vibraciones detectadas por sus sensores durante los días previos a la erupción. Esto permitirá reducir el riesgo de víctimas y destrozos materiales por este tipo de catástrofe natural.
El sistema de Jorge trabaja con 5 tipos de erupciones:

![Volcanos types](https://challenges-asset-files.s3.us-east-2.amazonaws.com/data_sets/Data-Science/4+-+events/jobmadrid/images/tipos.jpeg)

__Pliniana__: Se caracteriza por su alto grado de explosividad, con manifestaciones muy violentas en las cuales se expulsan grandes volúmenes de gas volcánico, fragmentos y cenizas.

__Peleana__: La característica más importante de una erupción peleana es la presencia de una avalancha brillante de ceniza volcánica caliente, llamada flujo piroclástico.

__Vulcaniana__: Son erupciones volcánicas de tipo explosivo. El material magmático liberado es más viscoso que en el caso de las erupciones hawaianas o estrombolianas; consecuentemente, se acumula más presión desde la cámara magmática conforme el magma asciende hacia la superficie.

__Hawaiana__: Consiste en la emisión de material volcánico, mayoritariamente basáltico, de manera efusiva o no explosiva. Ocurre de este modo debido a que la difusión de los gases a través de magmas más básicos (basálticos) puede hacerse de manera lenta pero más o menos continua. Consecuentemente, las erupciones volcánicas de este tipo no suelen ser muy destructivas.

__Estromboliana__: La erupción Estromboliana está caracterizada por erupciones explosivas separadas por periodos de calma de duración variable. El proceso de cada explosión corresponde a la evolución de una burbuja de gases liberados por el propio magma.

El __objetivo__ de este reto será__ ayudar a Jorge realizando el modelado predictivo__ a partir de un dataset que contiene las mediciones hechas por sus sensores y tipos.

Project to get access to the Hackathon organised by the IT-Academy and Decathlon. At the botton of this readme you can find the [initial information](##Initial-Info) shared throuhg the Nuwe platform[bottom]. [Train data set](https://github.com/MarkusHumetus/Access_Project_Hackathon_ITA_Decathlon/blob/main/Initial%20Docs/train.csv) and [Test data set](https://github.com/MarkusHumetus/Access_Project_Hackathon_ITA_Decathlon/blob/main/Initial%20Docs/test.csv) without the diagnosis/label column are in the initial Docs folder in this repository.
    
## Methodology

1. Inferential Statistics.
2. Exploratory, Analysis and manipulation of initial Data.
3. Screening classification by machine Learning.
4. Tunning of hyperparameters to optimize the chosen model.
5. Predict the status for the test data set (supplied without label) with the optimised model.

## Tools

* Python
* Git & Github
* Jupyter Notebook
* Visual Studio Code
* Libraries: Pandas, Numpy, Sweetviz, Seaborn, Matplotlib, Sklearn, Pycaret. 

## Getting Started

1. Clone this [repo](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022) (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Use [requirements.txt](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/requirements.txt) to install all required dependencies. Please note that Pycaret 2.3.0 only works properly under Python 3.6-3.8

## Project Status

[Finished]

Project was completed and submitted for competition in the 7th October  2022.
Files generated in the repository:
- [Jupyter Noebook](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/main.ipynb)

- [predictions.csv](https://github.com/MarkusHumetus/Access_Project_Hackathon_ITA_Decathlon/blob/main/predictions.csv)
- [requirements.txt](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/requirements.txt)

## Contact

If you have any comment, doubt, proposal,... don't hesitate to contact me by email to Marc.Humet.DataScience@gmail.com or by 
 [![LinkedIn][linkedin-shield]][linkedin-url]

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://www.linkedin.com/in/marchumetmontada/
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555


## Initial Info

🌌 Background
El càncer de mama és el més comú entre les dones del món. Representa el 25% de tots els casos de càncer i va afectar més de 2,1 milions de persones només el 2015. Comença quan les cèl·lules de la mama comencen a créixer de manera descontrolada. Aquestes cèl·lules solen formar tumors que es poden veure mitjançant raigs X o sentir-se com embalums a la zona del pit.

✅ Objectius
Comprendre el conjunt de dades i netejar-lo (si cal).

Construir models de classificació per predir si el tipus de càncer és maligne o benigne, variable "diagnosi" 0 benigne i 1 maligne.

També ajustar els hiperparàmetres i comparar les mètriques davaluació de diversos algorismes de classificació.

📈 Dataset
Per poder entrenar el model clickeu al següent link: Download train

I per poder avaluar-vos tindreu el següent conjunt de dades per al testeig: Download test

Submission
Per realizar l'entrega es demana un fitxer csv amb el nom "predictions.csv" on estará la columna de diagnosis amb un 0 o 1, en funció de si es benigne o maligne. Notar que cada fila del predictions correspon a la predicció de la fila del test amb les dades.

Evaluation
Per a l'avaluació es tindrà en compte el següent:

400/600: (OBJECTIUS) Això s'obtindrà a partir de la puntuació (macro) f1 del model predictiu. Comparant les prediccions que ha fet el vostre model sobre test_x versus la veritat terrestre.

200/600: (DOCUMENTACIÓ) S'avaluarà la documentació entregada en la s'expliqui la solució que han fet servir per resoldre el problema i el perquè l'han escollit.


## Acknowledgments

Thanks to the following organisations for the set up of such event which give the junior data scientist oportunities to learn, do networking and hopefully reach a first job in the data field.

![42Barcelona Fundación Telefonica](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/42_card.png)

![Barcelona Activa](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/bactiva_card.png)

![Barcelona Digital Talent](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/BDT_card.png)

![ITA_Academy](https://itacademy.barcelonactiva.cat/pluginfile.php/1/theme_remui/logo/1658314293/logo.png)



![Nuwe](https://elreferente.es/wp-content/uploads/2021/12/LOGO_LETTERS_MONO-3.png)

