# Energy Consumption

### The goal of this project is to forecast the power consumption of the Eastern United States Region Service by PJM
PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.
Source: Wikipedia (https://en.wikipedia.org/wiki/PJM_Interconnection)\n",
Note: The dataset was not gotten from wikipedia. The only information gotten from wikipedia is the explanatio of PJM and the areas they service."

This project identifies similar questions in a dataset using **Sentence Transformers** and **cosine similarity**.  
It groups related questions and exports the results with similarity scores and group IDs.

```bash
pip install -r requirements.txt
