# Federico Cocchi

![](images\union_jack.png){:height="25" width="25"}

English version of the Portfolio at the following [link](https://federico1-creator.github.io/Federico-Cocchi-En/)

---

Lista dei seminari frequentati al seguente [link](https://github.com/federico1-creator/seminars_followed/blob/main/README.md)

---

### [Image captioning](https://github.com/federico1-creator/AI4A)
Progetto per il corso di **AI for Automotive** - UNIMORE 2022

![](/images/AI4A.jpg){:height="200" width="400"}

Negli anni recenti i modelli Transformer-based hanno raggiunto lo stato dell'arte per quanto riguarda i Sequence model. 
In questo progetto si è implementato un sistema per Image captioning che 
considera come input immagini e testo (multimodal) per descrive attraverso il linguaggio naturale il contenuto dell'immagine.

Tranformer - Attention operator - Image captioning - COCO - CIDEr - Multimodal - text - image - Sequence model

---

### [Design a new pipeline to make a Virtual Try-On from a deep learning perspective](https://github.com/federico1-creator/CV-CS)
Progetto per il corso **Computer Vision & Cognitive Systems** - UNIMORE 2021

![](/images/VITON.jpg){:height="150" width="350"}

Creazione di una pipeline che permetta di creare un *camerino virtuale* per simulare la prova di nuovi abiti. Per questo progetto è stato utilizzato il dataset creato con la collaborazione di *Yoox*. 
In quest'ottica è stato implementato anche un sistema di *retrieval* che suggerisce all'utilizzatore i vestiti del catalogo più simili a quelli indossati.
Per creare la *trasformazione geometrica* che permette di simulare l'indossamento del nuovo abito si è utilizzata una rete neurale che permette di imparare la migliore trasformazione possibile.  

Python - Pytorch - Yoox - Retrieval - Virtual Try On - Semantic segmentation - Image processing - Geometric transformation

---

### [Reinforcement Learning with a single agent model free](https://github.com/federico1-creator/Distributed-AI)
Progetto per il corso **Distributed Artificial Intelligence** - UNIMORE 2021

![](/images/image.png){:height="150" width="350"}

<!---
![](https://github.com/federico1-creator/Distributed-AI/blob/main/data/exphigh_plus_benchmark.gif){:height="150" width="350"}
-->

Ho indagato l'utilizzo di singoli agenti model-free in vari environment, da quelli più semplici a quelli più complessi.
Inizialmente l'agente non conosce l'ambiente in cui opera, ma durante l'allenamento impara che azioni (policy) eseguire per completare correttamente il task.
Gli algoritmi utilizzati sono stati il Q-learning e DQN.
Ho anche paragonato tra loro i risultati ottenuti, considerando diversi hyperparameters.

Python - Gym - DQN - Q-learning - wandb - numpy

---

### [Hackathon on COVID-19](https://github.com/federico1-creator/covid-hackathon)
Progetto per hackathon su COVID-19

![](/images/final.jpg){:height="200" width="400"}

<!-- The purpose of this work is to define an explainable way to define if a COVID patient health status is "MILD" or "SEVERE" using an algorithm which elaborates this dataset. Each one of the following section explains one step of our classification pipeline. -->

L'obiettivo di questo lavoro è quello di trovare una modalità 'explainable' per definire se un paziente ha uno stato 'MILD' o 'SEVERE' rispetto alla patologia COVID-19; attraverso l'uso dell'algoritmo.
Nel paper viene descritta passo a passo l'architettura utilizzata per massimizzare la explainability del modello per poter aiutare l'operatore sanitario nell'interpretazione del risultato.

Semantic Segmentation - Pytorch - Classification - Decision tree - Medical images

---

### [CoViRo: control robot through a hand gesture recognition system](https://github.com/federico1-creator/gesture_robot)
Progetto per il corso **Smart Robotics** - UNIMORE 2022

![](/images/SR.jpg){:height="200" width="400"}

Tramite il lavoro di gruppo si è realizzata una simulazione del robot franka, controllato senza l'uso del controller ma tramite gesti.
Per far ciò si è realizzato un sistema di visione capace di classificare le diverse label indicate delle mani.
Sfruttando i keypoints ed una semplice Neural Network, siamo stati in grado di far ciò con un'elevata accuray (96%) ed in real time.
Questi due risultati (accuracy - real time) sono particolarmente importanti per una migliore interazione ed esperienza utente con il robot. 
Con le comunicazione di ROS si sono poi create le demo per mostrare le potenzialità del sistema implementato.
Controllando il robot con MoveIt ed il linguaggio cpp.

ROS - Python - cpp - RViz - MoveIt - Pytorch - MediaPipe - Franka robot

---

### [Anomaly prediction with Temporal Convolutional Networks and Data Augmentation in High Performance Computing Systems](https://github.com/federico1-creator/Thesis)
**Tesi di laurea triennale** - UNIBO 2020 

![](/images/prova_tesi_L.jpg){:height="200" width="450"}

Il lavoro di tesi ha indagato metodologie di anomaly prediction di anomalie nel sistema HPC LEONARDO situato presso il CINECA.
Si sono utilizzate tecniche di *machine learning*, creando una rete convoluzionale per analizzare le serie temporali in input.
Per migliorare le performance del sistema, si sono utilizzate anche tecniche di *data augmentation*, per ovviare all'elevato sbilanciamento nel dataset tra esempi corretti ed fault del sistema. 

Python - Tensorflow - Temporal series - Anomaly detection - High Performance Computing - Machine learning - Data augmentation

---

### [Health detector](https://github.com/federico1-creator/HEALTH-DETECTOR)
Progetto per il corso **IoT & 3D systems** - UNIMORE 2021 

![](/images/IoT.jpg){:height="200" width="400"}

Il progetto ha realizzato un sistema di monitoraggio della salute dei *pazienti/utenti* valutando diversi dati acquisiti da sensori controllati con Arduino. Con tali dati si è implementata una gestione web intelligente per predire lo stato di salute del paziente, basandosi sull'intelligenza artificiale per studiare l'evoluzione delle serie temporali.
Per facilitare la creazione di un possibile prototipo si è acquisito un modello 3D dell'oggetto tramite una nuvola di punti.
Il lavoro ha come obiettivo quello di fornire strumenti più efficaci al paziente ed al medico per valutare lo stato di salute ed agire con operazioni proattive in caso di necessità.

Arduino - IoT - Points cloud - 3D systems - Python - Flask - Server web - Temporal series

---

### [Re-design dell'interfaccia di un trattore New Holland del gruppo *CNH*](https://github.com/federico1-creator/HowIMetYourTractor)
Progetto per il corso **User Experience Design** - UNIMORE 2021 

![](/images/uxd.jpg){:height="200" width="400"}

Seguendo le fasi del *design cycle* inizialmente si sono fatte ricerche sui competitor ed analizzati diversi fattori sugli utenti utilizzando tecniche come personas, interviste, analisi degli scenari di utilizzo. Creando poi una House of quality con requisiti e richieste.
Una volta individuata l'idea si sono creati diversi concept (prima a bassa fedeltà e poi ad alta fedeltà) su cui eseguire delle analisi ergonomiche della cabina con il nuovo design per analizzare l'interazione con l'utente. In conclusione si sono svolti dei test di usabilità con dei volontari, per valutare oggettivamente il risultato del nuovo design.

QFD - Analisi ergonomiche - Concept - XD -Jack - House of quality 

---

### [INAFARM](https://github.com/federico1-creator/INAFarm)
Progetto per il corso **Innovation, development, entrepreneurship** presso **Almalabor**

![](/images/INAFARM.jpg){:height="200" width="400"}

Il progetto si è basato su una forte multidisciplinarietà del gruppo, che ha sviluppato una sua idea creativa fin dalle sue prime fasi di brain storming.
Per poi individuare l'idea e realizzarla tramite le attrezzature disponibili tramite il laboratorio Almalabor. 
Concludendo poi l'esperienza progettuale con la presentazione del risultato ottenuto.

Arduino - Team working - Multidisciplinarity - Laser cut - 3D printer

---

### [Confezionamento yogurt](https://github.com/federico1-creator/Progetto-macchina-yogourt)
Progetto per il corso di **Macchine automatiche**

![](/images/yogurt.jpg){:height="200" width="400"}

Studio e dimensionamento di una macchina automatica per il confezionamento dello yogurt. 
Valutazione di tutte le forze in atto e dei vari moti per individuare i vincoli di progetto e dimensionare i vari attuatori. 
Creazione di un modello 3D del sistema automatico di chiusura e movimentazione dei vasetti pieni di yogurt, con lo scopo di 
valutare le varie fasi di attuazione ed il sistema pneumatico necessario all'attuazione dei vari cilindri attuatori.

Diagrammi delle fasi - Grafcet -  Attuatori - Dimensionamenti - Sistema pneumatico

---
