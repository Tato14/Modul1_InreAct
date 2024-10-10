# **Iniciació a l'Ús de la IA en Salut**

Aquest repositori conté una sèrie de notebooks dissenyats per introduir els usuaris en l'ús de la Intel·ligència Artificial (IA) al sector de la salut. Els notebooks cobreixen diferents àrees de l'aprenentatge automàtic, incloent-hi aprenentatge supervisat, no supervisat i per reforç, i estan enfocats en aplicacions pràctiques i anàlisi de biaixos en models d'IA.

## **Contingut del Repositori**

1. [**Exploració de Dades i Detecció de Biaixos**](#1-exploració-de-dades-i-detecció-de-biaixos)
2. [**Predicció de Malalties**](#2-predicció-de-malalties)
3. [**Agrupament de Pacients**](#3-agrupament-de-pacients)
4. [**Simulació de Decisions Clíniques amb Aprenentatge per Reforç**](#4-simulació-de-decisions-clíniques-amb-aprenentatge-per-reforç)

---

### **1. Exploració de Dades i Detecció de Biaixos**

**Arxiu:** `Modul1_Lab1.ipynb`

**Descripció:**

En aquest notebook, explorem un conjunt de dades mèdiques relacionades amb malalties cardíaques. Realitzem una anàlisi exploratòria de dades per detectar possibles biaixos en variables demogràfiques com l'edat i el sexe. 

**Objectius:**

- Realitzar una anàlisi exploratòria de dades.
– Identificar i visualitzar distribucions de variables clau.
- Detectar possibles biaixos a les dades.
- Entendre la importància d'abordar els biaixos abans de modelar.

---

### **2. Predicció de malalties**

**Arxiu:** `Modul1_Lab2.ipynb`

**Descripció:**

Aquest nou notebook s'enfoca a construir un model d'aprenentatge supervisat per predir la presència de malalties cardíaques. A més, analitzem el rendiment del model en diferents subgrups demogràfics per identificar i entendre possibles biaixos a les prediccions.

**Objectius:**

- Preprocessar dades i preparar conjunts dentrenament i prova.
- Entrenar un model de classificació.
- Avaluar el rendiment del model utilitzant mètriques com a precisió, sensibilitat i especificitat.
- Analitzar el rendiment del model en subgrups demogràfics.

---

### **3. Agrupament de Pacients**

**Arxiu:** `Modul1_Lab3.ipynb`

**Descripció:**

En aquest notebook, apliquem tècniques d'aprenentatge no supervisat, específicament l'algorisme K-Means, per agrupar pacients basant-nos en característiques clíniques. Posteriorment, analitzem els grups formats per identificar possibles biaixos i disparitats entre diferents subgrups demogràfics.

**Objectius:**

- Aplicar tècniques de reducció de dimensionalitat (PCA).
- Utilitzar l'algorisme K-Means per agrupar dades.
- Visualitzar els clústers i entendre'n la composició.
- Analitzar possibles biaixos als grups formats.

---

### **4. Simulació de Decisions Clíniques amb Aprenentatge per Reforç**

**Arxiu:** `Modul1_Lab4.ipynb`

**Descripció:**

Aquest notebook implementa una simulació bàsica de decisions clíniques utilitzant tècniques daprenentatge per reforç. Creem un entorn simulat on un agent aprèn a seleccionar el millor tractament per a pacients, basant-se en les recompenses obtingudes dels resultats de salut.

**Objectius:**

- Definir un entorn simulat per a laprenentatge per reforç.
- Implementar un agent que fa servir l'algorisme Q-Learning.
- Entrenar l'agent perquè aprengui la política òptima.
- Avaluar i visualitzar els resultats de laprenentatge.

---

## **Instruccions per utilitzar els Notebooks**

1. **Clonar el Repositori:**

 ```bash
 git clone https://github.com/Tato14/Modul1_InreAct.git
 ```

2. **Accedir a la carpeta del Repositori:**

 ```bash
 cd nom_del_repositori
 ```

3. **Obrir els Notebooks:**

- Pots obrir els notebooks utilitzant [Jupyter Notebook](https://jupyter.org/install) o [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html).
- Alternativament, podeu carregar-los a [Google Colab](https://colab.research.google.com/):
 Aneu a Fitxer > Pujar notebook i seleccioneu el fitxer `.ipynb` que voleu obrir.

## **Treballar Directament a Google Colab**

 - Pots obrir els notebooks directament a [Google Colab](https://colab.research.google.com/):
    - Ves a Arxiu > Obrir Quadern
    - Vés a la pestanya "Github" ia la URL afegeix la del repositori: "https://github.com/Tato14/Modul1_InreAct"
    - Selecciona el notebook amb què vols treballar