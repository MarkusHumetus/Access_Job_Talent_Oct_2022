# Intro/Objectives: Project to access the Hackathon from JobTalent Hackathon on 17th October 2022

Project to get access to the Hackathon organised by 42Barcelona, Barcelona Activa and Barcelona Digital Talent. At the botton of this readme you can find the [initial information](#Initial-Info) shared throuhg the Nuwe platform. [Train data set](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/initial_files/jm_train.csv) and [Test data set](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/initial_files/jm_X_test.csv) without the diagnosis/label column are in the [initial Docs folder](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/tree/main/initial_files) in this repository.

    
# Methodology

0. Load libraries and data.
1. Exploratory, Analysis and manipulation of initial Data (Sweetviz library used).
2. Data Engineering
3. Study Data Engineering impact on model performance
4. Tunning of hyperparameters to optimize the Random Forest model.
5. Predict the status for the test data set (supplied without label) with the optimised model.
6. Results and conclusions

# Tools

* Python
* Git & Github
* Jupyter Notebook
* Visual Studio Code
* Libraries: Pandas, Numpy, Sweetviz, Seaborn, Matplotlib, Sklearn, Pycaret, Optuna. 

# Getting Started

1. Clone this [repo](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022) (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Use [requirements.txt](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/requirements.txt) to install all required dependencies. Please note that Pycaret 2.3.0 only works properly under Python 3.6-3.8

# Project Status

[Finished]

Project was completed and submitted for competition in the 7th October  2022.
Files generated in the repository:
- [Jupyter Noebook: main.ipynb](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/main.ipynb)

- [predictions.csv](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/predictions.csv)
- [requirements.txt](https://github.com/MarkusHumetus/Access_Job_Talent_Oct_2022/blob/main/requirements.txt)

# Initial Info

Jorge es un ge??logo del IGME (Instituto Geol??gico y Minero de Espa??a) que est?? desarrollando un nuevo sistema de prevenci??n de erupciones para poder predecir qu?? tipo de erupci??n tendr?? un volc??n seg??n las las vibraciones detectadas por sus sensores durante los d??as previos a la erupci??n. Esto permitir?? reducir el riesgo de v??ctimas y destrozos materiales por este tipo de cat??strofe natural.
El sistema de Jorge trabaja con 5 tipos de erupciones:

![Volcanos types](https://challenges-asset-files.s3.us-east-2.amazonaws.com/data_sets/Data-Science/4+-+events/jobmadrid/images/tipos.jpeg)

__Pliniana__: Se caracteriza por su alto grado de explosividad, con manifestaciones muy violentas en las cuales se expulsan grandes vol??menes de gas volc??nico, fragmentos y cenizas.

__Peleana__: La caracter??stica m??s importante de una erupci??n peleana es la presencia de una avalancha brillante de ceniza volc??nica caliente, llamada flujo pirocl??stico.

__Vulcaniana__: Son erupciones volc??nicas de tipo explosivo. El material magm??tico liberado es m??s viscoso que en el caso de las erupciones hawaianas o estrombolianas; consecuentemente, se acumula m??s presi??n desde la c??mara magm??tica conforme el magma asciende hacia la superficie.

__Hawaiana__: Consiste en la emisi??n de material volc??nico, mayoritariamente bas??ltico, de manera efusiva o no explosiva. Ocurre de este modo debido a que la difusi??n de los gases a trav??s de magmas m??s b??sicos (bas??lticos) puede hacerse de manera lenta pero m??s o menos continua. Consecuentemente, las erupciones volc??nicas de este tipo no suelen ser muy destructivas.

__Estromboliana__: La erupci??n Estromboliana est?? caracterizada por erupciones explosivas separadas por periodos de calma de duraci??n variable. El proceso de cada explosi??n corresponde a la evoluci??n de una burbuja de gases liberados por el propio magma.

???? __Objectivo__

El __objetivo__ de este reto ser??__ ayudar a Jorge realizando el modelado predictivo basado en Random Forests que permita conocer el tipo de erupci??n que tendr?? un volc??n en funci??n de las vibraciones medidas por los sensores.

Una vez se haya hecho y entrenado el modelo predictivo, este se tendr?? que emplear con los features del dataset de testing 'jm_test_X.csv'. Estas predicciones se tendr??n que entregar en formato csv como en el ejemplo. Donde tendr?? que aparecer tan solo una columna en la que en la primera fila sea un texto cualquiera y las predicciones empiecen en la fila 2.

La calidad de la predicci??n se medir?? a partir del f1-score (macro).


???? __Dataset__

Features: El dataset contiene 6 features en 6 columnas, que son los par??metros medidos por los diferentes sensores. Estos corresponden a las vibraciones detectadas en ciertos puntos de la ladera del volc??n.

Target: El target corresponde al 'label' que clasifica los tipos de erupciones volc??nicas en funci??n de los features medidos por los sensores.

Target 0 corresponde a una erupci??n de tipo Pliniana
Target 1 corresponde a una erupci??n de tipo Peleana
Target 2 corresponde a una erupci??n de tipo Vulcaniana
Target 3 corresponde a una erupci??n de tipo Hawaiana
Target 4 corresponde a una erupci??n de tipo Estromboliana

??? __Evaluaci??n__
La evaluaci??n se basar?? en los objetivos cumplidos (900/1200), en la calidad de c??digo (200/1200)  y en la documentaci??n (100/1200).

???? __Entrega__
Se deber?? pegar el link a tu repositorio de Github/Gitlab en el que haya un archivo (.ipynb o .py) con todo el c??digo escrito y un archivo predictions.csv con las predicciones de tu modelo.

# Contact

If you have any comment, doubt, proposal,... don't hesitate to contact me by email to Marc.Humet.DataScience@gmail.com or by 
 [![LinkedIn][linkedin-shield]][linkedin-url]

<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-url]: https://www.linkedin.com/in/marchumetmontada/
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555


# Acknowledgments

Thanks to the following organisations for the set up of such event which give the junior data scientist oportunities to learn, do networking and hopefully reach a first job in the data field.

![42Barcelona Fundaci??n Telefonica](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/42_card.png)

![Barcelona Activa](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/bactiva_card.png)

![Barcelona Digital Talent](https://challenges-asset-files.s3.us-east-2.amazonaws.com/companies/BDT_card.png)

![ITA_Academy](https://itacademy.barcelonactiva.cat/pluginfile.php/1/theme_remui/logo/1658314293/logo.png)

![Nuwe](https://elreferente.es/wp-content/uploads/2021/12/LOGO_LETTERS_MONO-3.png)

