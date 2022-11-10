## codeless data mining
# Measuring Similarity English Translations of Surah Al-Fatihah using Computational Methods 
### Arif Yacop 
### 3rd year Data science and Analytics Deparment of science and technology Fatoni University 


# Overview
similarity evaluation between different English translation of Surah Al-Fatihah by using computational method is perfomed. 


## Data (Alquran english translation)
[16 translation of surah Al-fatihah](/15-English-Quran-Al-Fatihah-Translation/english-quran-al-fatihah-translation.xlsx)

![](/img/data.png)
7 row, 19 column

## tool
- excel
- knime
- github

## step to do 
## Preprocessing 
1. data access
![](/img/excel%20reader.png)

![](/img/r1.png)
2. transfrom data 
![](/img/tranfrom%20data%20.png)

![](/img/r2.png)

3. data processing 
 ![](/img/text%20process.png)


 - string to document 
 - POS Tagger
 - Stanford Tadder
 - Punctuation Erasure
 - Stop word Fiter
 - Case Converter
 - Snowball stemmer
 - N Chars filter
 - Bag of word creater


![](/img/r3.png)

 # Model
 ## First Way 
 ![](/img/w1.png)
 ### TF-IDF
 ![](/img/TF-IDF.png)

 use formula TF * IDF 

 ## Secone Way 
 ![](/img/w1.png)
 ### TF-IDF
 ![](/img/TF-IDF.png)

 use formula TF log(IDF) 

 # Test

### Cosine Similarity 
 ![](/img/cosine%20.png)
 
 

 




# Result

### First Way  
![](/img/r4.png)

### Second Way
![](/img/r5.png)

## Conclution 
math for formula is very importent for find weigh of frequency