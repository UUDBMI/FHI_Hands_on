# Using Natural Language Processing to Indentify Patients with Family History of Breast and/orColon Cancer

## Case Study Outcomes 

1.  Develop a rule-based nlp pipeline from templates, and fine tune the rules
2.  Use python and jupyter notebook to execute the NLP pipeline
3.  Visualize NLP output
4.  Preform error analyses and evaluation; Compare Trade-offs between recall and precision
5.  Identify nuances in NLP development

## Pre-Requisite Skills

In order to participate in this module the student should have the following skills and knowledge

1.  Basic knowledge and familiarity with python and jupyter notebook
2.  Basic skill of using git
3.  Basic understanding of family history, breast cancer, colon cancer.
4.  Basic knowledge of regular expression

## Data Science Components with Associated Knowledge and Skill Sets

### **Knowledge Representation**

1.  Identify patient family history of breast cancer or colon cancer from clinical notes
1.  Gain rule-based NLP knowledge and skills

### **Computation**

1.  Use python to build a rule-based NLP pipeline
1.  Use python to evaluate NLP performance

### **Visualization**

1.  Use built-in packages to visualize the NLP output

### **Statistical Analysis**

1.  Contingency tables
1.  NLP performance measurements

## Case Study Materials 

1.  [**GitHub Repository**](https://github.com/UUDBMI/FHI_Hands_on)
2.  [**MIMIC II*** ***demo dataset**](https://physionet.org/mimic2/demo/)
3.  [**Bibliography**]() 

This project demonstrates how to use [pyConText](https://github.com/chapmanbe/pyConTextNLP) to identify the patients with family history of breast cancer and/or colon cancer, with the nice real time visualization adopted from the Brat's design [2]. For example，

![pycontext visual](/img/snapshot3.png)



Use the following bash commnad in terminal to clone the notebooks into your local directory.
```bash
git clone https://github.com/jianlins/FHI_Hands_on.git
```
If you are using [jupyterhub.med.utah.edu](http://jupyterhub.med.utah.edu), you will need to open the remote 'terminal' through the jupyter's web interface.   
![remote terminal](/img/snapshot11.png)

Then execute the following commands:  
![remote terminal](/img/snapshot12.png)


The dataset for this project is sampled from [MIMIC demo dataset](https://physionet.org/mimic2/demo/) [1].  
The visualization tool used in this project is derived from [arne-cl's project](https://github.com/arne-cl/brat-embedded-visualization-examples/tree/master/js), which is made out of [Brat](http://http://brat.nlplab.org)[2].  

## References:
1. MIMIC-III, a freely accessible critical care database. Johnson AEW, Pollard TJ, Shen L, Lehman L, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. Scientific Data (2016). DOI: 10.1038/sdata.2016.35. Available at: http://www.nature.com/articles/sdata201635
2. BRAT:A Web-based Tool for NLP-Assisted Text Annotation. PontusStenetorp, SampoPyysalo, GoranTopic, TomokoOhta, Sophia Ananiadou, and Jun’ichi Tsujii. In Proceedings of the European Chapter of the Association for Computational Linguistics (2012), pages 102–107
  
  
    
<br/><hr/>This material presented as part of the Foundations of Healthcare Informatics Course, 2017 Fall, BMI, University of Utah. It's revised from the <a href="https://github.com/UUDeCART/decart_rule_based_nlp">material</a> of the DeCART  Summer Program (Data, exploration, Computation, and Analytics Real-world Training for the Health Sciences) at the University of Utah in 2017. <br/><br/>Original presenters : Dr. Wendy Chapman, Jianlin Shi and Kelly Peterson.<br/>
Revised by: Jianlin Shi and Dr. Wendy Chapman<br/>
<img align="left" src="https://wiki.creativecommons.org/images/1/10/Cc.org_cc_by_license.jpg" alt="Except where otherwise noted, this website is licensed under a Creative Commons Attribution 3.0 Unported License.">
