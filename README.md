# Sentiment aided Virtual Assistant (VA) : SentiVA

## This is the readme file that contains the information about the SentiVA dataset introduced in the following paper

**Paper Name:-** Towards sentiment aided dialogue policy learning for multi-intent conversations using hierarchical reinforcement learning
>Developing a Dialogue/Virtual Agent (VA) that can handle complex tasks (need) of the user pertaining to multiple intents of a domain is challenging as it requires the agent to simultaneously deal with multiple subtasks. However, majority of these end-to-end dialogue systems incorporate only user semantics as inputs in the learning process and ignore other useful user behavior and information. Sentiment of the user at the time of conversation plays an important role in securing maximum user gratification. So, incorporating sentiment of the user during the policy learning becomes even more crucial, more so when serving composite tasks of the user. As a first step towards enabling the development of sentiment aided VA for multi-intent conversations, this paper proposes a new dataset, annotated with its corresponding intents, slot and sentiment (considering the entire dialogue history) labels, named SentiVA, collected from open-sourced dialogue datasets. In order to integrate these multiple aspects, a Hierarchical Reinforcement Learning (HRL) specifically options based VA is proposed to learn strategies for managing multi-intent conversations. Along with task success based immediate rewards, sentiment based immediate rewards are also incorporated in the hierarchical value functions to make the VA user adaptive. Empirically, the paper shows that task based and sentiment based immediate rewards cumulatively are required to ensure successful task completion and attain maximum user satisfaction in a multi-intent scenario instead of any of these rewards alone. This work is the first attempt in incorporating sentiment based rewards in the HRL framework.

* **Authors:** Tulika Saha, Sriparna Saha and Pushpak Bhattacharyya
* **Affiliation:** Indian Institute of Technology Patna, India
* **Corresponding Author:** [Tulika Saha] (sahatulika15@gmail.com)
* **Accepted(June, 2020):**  [PLOS ONE Journal](https://doi.org/10.1371/journal.pone.0235367)


If you consider this dataset useful, please cite it as

```bash
@article{saha2020towards,
  title={Towards sentiment aided dialogue policy learning for multi-intent conversations using hierarchical reinforcement learning},
  author={Saha, Tulika and Saha, Sriparna and Bhattacharyya, Pushpak},
  journal={PloS one},
  volume={15},
  number={7},
  pages={e0235367},
  year={2020},
  publisher={Public Library of Science San Francisco, CA USA}
}
```

# Description

1. SentiVA dataset is curated by collecting conversations from an open sourced dialogue dataset named bAbI.
2. The bAbI dataset contains conversations for a set of 6 tasks for testingend-to-end dialog systems in the Restaurant domain. Dialogues pertaining to task-4 and 5 were utilized to prepare conversations for the SentiVA dataset.
3. The conversations from the bAbI dataset has been manually modified and annotated for the corresponding intent, slot and sentiment labels to make it suitable for developing a sentiment aided VA for multi-intent conversations.
4. SentiVA dataset contains conversations concerning several multi-intents such as restaurant_info, restaurant_book, restaurant_phone, restaurant_address involving slots or entities such as location, cuisine, no. of people, restaurant name and price.
  
# Contact
  
For any queries, feel free to contact the corresponding author Tulika Saha (sahatulika15@gmail.com) 
