# Lymphoma ML project


## Try our sponsor to earn some free cute dogecoins.
<a href="https://clowerty.cc/ref/cancer.research.data.inside"><img src="https://clowerty.cc/advertising/468.gif"></a>
<a href="https://bluemagic.cloud/ref/cancer.research.data.inside"><img src="https://bluemagic.cloud/advertising/468.gif"></a>

Instruction:
1. Click the [link](https://bluemagic.cloud/ref/cancer.research.data.inside) and register an account.
2. After register and login
3. Click on Dashboard
3. Select mining and adjust dogecoin to 100%.
4. Now you will see the number under dogecoin increasing. 

We believe dogecoins are loves, cares and encourages. Now you are seeing loves, cares and encourages being generated continuously. 


Even this guy love this cute coin.

![dogecoin imag](https://media.marketrealist.com/brand-img/v_4P0jrvF/2160x1131/should-i-buy-dogecoin-1608570181018.jpg)

## It seems he plan to take dogecoins with him to stars! ;)

![doecions at stars](https://www.supercryptonews.com/wp-content/uploads/2020/07/417578-1024x574-3.jpg)

## Share some loves and cares if you have plenty of them:

![Donate Dogecoin to cancer-research-data-inside](cancer-research-data-inside-dogecoin.png)


We appreciate Jindong and other volunteers help! If you are interested in this project, please contact data_inside@outlook.com attn: Jindong Pan.

You welcome to send your sample images to cancer.research.data.inside@gmail.com with subject:"lymphoma sample ML test".

All comments are welcome:
- Medical professional can feedback at our [medical professional wiki page](https://github.com/cancer-research-data-inside/lymphoma/wiki/Medical-professional-discussion-page).
- Data scientist comments go [data analysis wiki page](https://github.com/cancer-research-data-inside/lymphoma/wiki/data-analysis-discussion-page).
- Other comments go [guest wiki page](https://github.com/cancer-research-data-inside/lymphoma/wiki/Guest-wiki-page).

Let's make data help people and save lifes!

# Basic info. of the project

Datasets:
- 100 CCL samples in CCL directory
- 100 FL  samples in FL directory
- 100 MCL samples in MCL directory

Each sample cut into 30 small patches and random flipped and spined to train and test model.

We use 90% data train model and hold 10% data test model

Initial result:
We are able to improve the model accuracy from 86% to 97%
The project is tempory on hold and waiting for medical professionals input to make sure it is meaningful.

# Model test summary:
```
Confusion matrics index: ['CLL', 'FL', 'MCL'] 

[[252.   6.  12.]
 [  2. 205.   3.]
 [  0.   2. 418.]]
Accuracty:	0.9722222222222222
```

# Model test summary grouped by patient ID:


## Each sample cut by 30 small patches
labels in matrix: 0:CCL, 1:FL, 2:MCL

*Person id*:v0  Sample filename: b'./FL/sj-05-1881-R1_018.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[1 1 2 0 1 1]
 [1 1 1 1 1 1]
 [1 1 1 1 1 1]
 [1 1 1 1 1 1]
 [1 1 0 1 1 1]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[ 0  0  0]
 [ 2 27  1]
 [ 0  0  0]]
```
--------------------------------------------------
*Person id*:v1  Sample filename: b'./CLL/sj-03-5521_006.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[2 2 2 0 0 2]
 [2 2 2 0 0 0]
 [0 2 0 0 0 0]
 [0 0 0 0 2 0]
 [0 0 0 2 2 0]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[19  0 11]
 [ 0  0  0]
 [ 0  0  0]]
```
--------------------------------------------------
*Person id*:v2  Sample filename: b'./FL/sj-05-894-R3_008.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v3  Sample filename: b'./MCL/sj-04-6010-R3_011.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[2 2 2 2 2 1]
 [2 2 2 2 2 2]
 [2 2 2 2 2 2]
 [2 2 2 2 2 2]
 [2 2 2 2 2 2]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[ 0  0  0]
 [ 0  0  0]
 [ 0  1 29]]
```
--------------------------------------------------
*Person id*:v4  Sample filename: b'./CLL/sj-03-476_009.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v5  Sample filename: b'./MCL/sj-04-4967-R2_011.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v6  Sample filename: b'./MCL/sj-05-768_004.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v7  Sample filename: b'./MCL/sj-05-4179-R1_002.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v8  Sample filename: b'./MCL/sj-05-768_014.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v9  Sample filename: b'./CLL/sj-03-5521_005.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v10  Sample filename: b'./MCL/sj-05-768_013.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v11  Sample filename: b'./FL/sj-05-588-R1_003.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v12  Sample filename: b'./MCL/sj-05-1374_001.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v13  Sample filename: b'./MCL/sj-05-3362-R2_013.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v14  Sample filename: b'./CLL/sj-05-3344_002.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[0 1 0 0 0 0]
 [0 0 0 0 0 0]
 [0 0 0 0 0 0]
 [0 0 0 1 0 0]
 [0 0 0 1 0 0]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[27  3  0]
 [ 0  0  0]
 [ 0  0  0]]
```
--------------------------------------------------
*Person id*:v15  Sample filename: b'./FL/sj-05-1881-R1_001.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[1 1 1 1 1 1]
 [1 1 1 1 1 1]
 [1 1 1 1 1 1]
 [1 1 1 1 1 1]
 [1 1 1 1 2 2]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[ 0  0  0]
 [ 0 28  2]
 [ 0  0  0]]
```
--------------------------------------------------
*Person id*:v16  Sample filename: b'./FL/sj-05-588-R1_010.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v17  Sample filename: b'./CLL/sj-05-1396-R3_005.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v18  Sample filename: b'./MCL/sj-04-3077-R2_002.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[2 2 2 2 2 2]
 [2 2 2 2 2 2]
 [2 2 2 2 2 1]
 [2 2 2 2 2 2]
 [2 2 2 2 2 2]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[ 0  0  0]
 [ 0  0  0]
 [ 0  1 29]]
```
--------------------------------------------------
*Person id*:v19  Sample filename: b'./FL/sj-05-894-R3_001.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v20  Sample filename: b'./MCL/sj-04-3077-R2_010.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v21  Sample filename: b'./CLL/sj-05-3874-R2_002.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v22  Sample filename: b'./MCL/sj-04-6010-R3_006.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v23  Sample filename: b'./CLL/sj-03-852-R2_006.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v24  Sample filename: b'./CLL/sj-03-5521_004.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v25  Sample filename: b'./MCL/sj-05-1374_014.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v26  Sample filename: b'./FL/sj-05-5389-R1_009.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v27  Sample filename: b'./MCL/sj-04-4525-R4_003.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v28  Sample filename: b'./MCL/sj-04-3077-R2_006.tif'
```
All patches 100% matched
```
--------------------------------------------------
*Person id*:v29  Sample filename: b'./CLL/sj-03-4957_007.tif'
```
predict patch matrix 0:CCL, 1:FL, 2:MCL:
 [[0 0 0 0 0 0]
 [0 0 0 0 0 0]
 [0 0 0 1 0 0]
 [0 0 0 1 0 0]
 [2 0 0 1 0 0]]
Confusion matrics index: ['CLL', 'FL', 'MCL'] 
 [[26  3  1]
 [ 0  0  0]
 [ 0  0  0]]
```
--------------------------------------------------
Reference:
https://lymphoma.org/

**Lymphoma** is the most common type of blood cancer.  Specifically, lymphoma is a cancer that affects lymphocytes, which are a type of white blood cell. Lymphocytes travel through the blood and lymphatic system to defend the body against foreign invaders like bacteria and viruses.  **Lymphoma**s usually develop when a change, or mutation, occurs within a lymphocyte, causing the abnormal cell to replicate faster than, or live longer than, a normal lymphocyte.  Like normal lymphocytes, cancerous lymphocytes can travel through the blood and lymphatic system and spread and grow in many parts of the body, including the lymph nodes, spleen, bone marrow, and other organs.<br/>

Three major categories of cancers that affect lymphocytes are:<br/>
Chronic Lymphocytic Leukemia/Small Lymphocytic **Lymphoma** (**CLL/SLL**): CLL/SLL are the same disease with slightly different manifestations. Where the cancerous cells gather determines whether it is called CLL or SLL. Leukemic cells develop because of a change that takes place in the cell’s DNA. Approximately 19,000 people are diagnosed with CLL/SLL in the United States each year.

Hodgkin **Lymphoma** (HL): There are five types of HL, an uncommon form of lymphoma that involves the Reed-Sternberg cells. Approximately 9,000 people are diagnosed with HL in the United States each year.<br/>

Non-Hodgkin **Lymphoma** (NHL): There are more than 90 types of NHL, some of which are more common than others. Any lymphoma that does not involve Reed-Sternberg cells is classified as non-Hodgkin lymphoma. Approximately 80,000 people are diagnosed with NHL each year in the United States.

Mantle cell lymphoma is a rare form of cancer of the immune system. In **MCL**, abnormal B cells that originate in the mantle zone, or outer edge, of the lymph node, grow out of control. MCL is a type of B cell non-Hodgkin lymphoma.

Follicular lymphoma (**FL**) is typically a slow-growing or indolent form of non- Hodgkin lymphoma (NHL) that arises from B-lymphocytes, making it a B-cell lymphoma. This lymphoma subtype accounts for 20 to 30 percent of all NHL cases.


Signs and Symptoms
Certain symptoms are not specific to lymphoma and are, in fact, similar to those of many other illnesses. People often first go to the doctor because they think they have a cold, the flu or some other respiratory infection that does not go away.
Common symptoms include:

    - Swelling of lymph nodes, which may or may not be painless
    - Fever
    - Unexplained weight loss
    - Sweating (often at night)
    - Chills
    - Lack of energy
    - Itching
    
Most people who have these non-specific symptoms will not have lymphoma. However, it is important that anyone with persistent symptoms be examined by a doctor to make sure lymphoma is not present.

