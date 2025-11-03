### LLM et Fine-tuning

---




## Question 1
> [!CAUTION]
> Vous avez besoin de vous créer à un moment un compte sur hugginface et surtout de générer (profile/access_token/) un token, ce token doit être un
**TOKEN TYPE : WRITE*, et penser idéallement à le sauvegarder car vous ne pourrez plus le consulter
>
> Vous devrez aussi demander sur ce même compte, l'agrement à Meta  d'utiliser ce modele https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct. La procedure prend en general 30' avant accord de Meta

[Colab LLM Fine-tuning](https://colab.research.google.com/github/fabricejumel/5ETI20252026-DEEPLEARNING-/blob/main/Fine_Tune_Llama_3_1B_LORA64_PIAF_CPE.ipynb)



**1.a** À quoi correspond le site Hugging Face Hub cité dans le document ? Créez-vous un compte.

**1.b** Concernant les tutoriels disponibles, ils sont très nombreux. Si le sujet vous intéresse, vous pourrez les regarder, mais cela n’est pas demandé :
- [Cours de NLP](https://huggingface.co/learn/nlp-course/)
- [Classification de séquence](https://huggingface.co/docs/transformers/tasks/sequence_classification)
- [Classification de token](https://huggingface.co/docs/transformers/tasks/token_classification)
- [Question answering](https://huggingface.co/docs/transformers/tasks/question_answering)
- [Modélisation de langage](https://huggingface.co/docs/transformers/tasks/language_modeling)
- [Modélisation de langage masqué](https://huggingface.co/docs/transformers/tasks/masked_language_modeling)
- [Traduction](https://huggingface.co/docs/transformers/tasks/translation)
- [Résumé automatique](https://huggingface.co/docs/transformers/tasks/summarization)
- [Tutoriel LLM](https://huggingface.co/docs/transformers/llm_tutorial)

**1.c** Quel est le nom du modèle de réseau sous-jacent ? Quelle est sa taille et son architecture ?

**1.d** A quoi correspond le "Instruct" 

**1.e** Le modèle est-il déjà entraîné ou est-ce simplement une structure de réseau ?

**1.f** Si le modèle est déjà entraîné, sur quels datasets a-t-il été formé ?

**1.g** Quelle puissance de calcul en TFlops a été nécessaire pour l'apprentissage initiale

**1.h** Qu’est-ce qu’un LoRA ? Expliquez ses 3 paramètres.

**1.i** Qu’est-ce qu’un Transformer ? Expliquez son usage dans le cadre d’un LLM.

**1.j** Si ce n’est pas déjà fait, lancez l’exécution de l’ensemble du code (cela prend environ 30 minutes).

---

## Question 2

**2.a**  En quoi consiste la notion de *token* ? Donnez des exemples de tokens dans notre cas.
**2.b** A quoi correspondent les embedded words dans ce modele  ?

---

## Question 3

Le but de ce code est de procéder à un *fine-tuning* du modèle.

**3.a** De quoi parle-t-on ici ?

**3.b** Quel est le dataset utilisé ? Montrez des exemples et indiquez sa taille. Quelle puissance de calcul en TFlops a été nécessaire pour le *fine-tuning* ? A-t-on modifié la taille du modèle après apprentissage ?

**3.c** Expliqueez pourquoi et comment le dataset a été modifié pour le finetuning

---

## Question 4


**4.a** que pensez vous de l'évolution du "Loss" pednant l'apprentissage

**4.b** Comment est il précisementcalculé, donné des exemples concrets

**4.c** Testez différents prompts. Que pensez-vous de ses performances ? Comparez les résultats avec ChatGPT.

---

## Question 5

**5.a** Refaites les tests en partant du même modèle sans le *fine-tuning*. 

**5.b** Tester sur des exemples issus du dataset d'apprentissage

**5.b** En vous inspirant du dataset utilisé , trouvé des cas pertinent où l'apprentissage a servi à quelque chose 

---

## Question 6

Proposer une liste de différents LLM utilisables pour faire du finetuning,  quelles sont les caractéristqiues des machines nécessaires (minimum et idéal) pour les utiliser en inference et pour les fine tuner .

## Question 7 (Exploratoire)

Quelles sont les différentes outils proposés classiquement pour faire du finetuning de LLM ?

## Question 8 (Exploratoire)

Proposez un *fine-tuning* particulier en trouvant un dataset original. Quelle est la taille conseillée pour ce dataset. Montrez en quoi les résultats sont mauvais avant le *fine-tuning*, puis montrez le résultat après. Êtes-vous satisfait ?

## Question 9 (Exploratoire)

Comment peut on representer le fonctionnement d'un LLM, de manière pertinente et imagée . Faites une proposition. Comment  représenter le avant / après du finetuning "graphiquement"



