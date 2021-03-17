# DeCoviD

Detection of Covid-19 related markers of pulmonary changes using Deep Neural Networks models supported by eXplainable Artificial Intelligence and Cognitive Compressed Sensing

## Description

The aim of the DeCoviD project is to develop methods and tools to support radiologists in the assessment of lung imaging data for the occurrence of changes caused by Covid-19 disease. The developed solution will allow to automate the identification of pathological changes and will support the diagnosis of coexisting lung diseases as well as diseases of other organs visible on chest images. It will also allow to quantify the severity of lung damage caused by the disease.

Responsible decision support for radiologists requires models based on interpretable features. Such features will be stored in a hybrid knowledge base powered by two research teams from the Warsaw University of Technology, working on the basis of two, seemingly opposite, paradigms of image data analysis. The Explainable Artificial Intelligence (XAI) team will use trained deep networks to automatically extract features that are essential for effective disease detection. Cognitive Compressed Sensing (CCS) will build a set of interpretable semantic features using sparse cognitive representations agreed with a group of cooperating radiologists. Combining these two approaches will achieve high effectiveness of the constructed models, combined with high transparency, clarity and stability of the solution.

To train deep neural networks we will use the available image data repositories for patients after Covid-19 [Cohen2020, Chung2020, Chowdhury2020, Born2020, Zhao2020, ...] and other lung diseases [Summers2017, Bustos2019]. Machine learning models will be confronted with the domain knowledge of cooperating radiologists and supported by sparse representations of trained dictionaries driven by ontological knowledge.

The DeCoviD project is a part of a broader strategy of competence development in the area of Deep Learning + XAI + medical applications at the Warsaw University of Technology.

![Solution architecture](https://github.com/MI2DataLab/DeCovid-19/blob/master/Solution_architecture.png?raw=true)

## Acknowledgments

This research was partially funded by [IDUB against COVID-19](https://badawcza.pw.edu.pl/Konkursy/Wyniki-konkursow/Wyniki-konkursu-IDUB-against-COVID-19) project granted by Warsaw University of Technology under the program [Excellence Initiative: Research University (IDUB)](https://inicjatywadoskonalosci.uw.edu.pl/en/programme). 
