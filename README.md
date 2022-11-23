# Lymphography Dataset using Neural Networks
Here, I use Lymphography dataset to perform Neural Networks.

## Building a Deep Learning model on Lymphography Dataset

The Lymphatic system is a network of vessels that transports a clear fluid called lymph around your body. The lymphatic system also includes glands(called lymph nodes)
 and lymph organs. Lymphangiography is an imaging technique used to provide precise information on the extent and location of lymph vessels and lymph nodes.
 
About: This is one of three domains provided by the Oncology Institute that has repeatedly appeared in the machine learning literature. (See also breast-cancer and primary-tumor.)

Target Variable:

- class: normal find, metastases, malign lymph, fibrosis

Features:

- lymphatics: normal, arched, deformed, displaced

- block of affere: no, yes

- bl. of lymph. c: no, yes

- bl. of lymph. s: no, yes

- by pass: no, yes

- extravasates: no, yes

- regeneration of: no, yes

- early uptake in: no, yes

- lym.nodes dimin: 0-3

- lym.nodes enlar: 1-4

- changes in lym.: bean, oval, round

- defect in node: no, lacunar, lac. marginal, lac. central

- changes in node: no, lacunar, lac. margin, lac. central

- changes in stru: no, grainy, drop-like, coarse, diluted, reticular, stripped, faint,

- special forms: no, chalices, vesicles

- dislocation of: no, yes

- exclusion of no: no, yes

- no. of nodes in: 0-9, 10-19, 20-29, 30-39, 40-49, 50-59, 60-69, >=70

The aims to develop a model to enhance lymphatic diseases diagnosis by the use of Machine learning and Deep learning models with different architectures, we will see how Machine LearningL models perform in comparsion to Deep Learning models.

This study has been carried out in two major phases:

- In the first stage, with out considered Oversample/Upsample method, analyzed and built ML and DL models. This step did not improve the classification performance.
- In the second stage, used the Oversample/Upsample method analysed and build the ML and DL models.

In this analysis, a approach has been investigated to improve the diagnosis of lymph diseases by Oversample and Hyperparameter tuning on DL and ML algorithms. 
