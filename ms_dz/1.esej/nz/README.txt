NOVI ZELAND

O lokacijama snimanja Gospodara prstenova, stočarstvu, kiviju, himnama i jezicima Novog Zelanda. 


UPUTE ZA POKRETANJE: (win Anaconda Prompt, linux Terminal)

#Ako nemate, dodajte channel conda-forge:
conda config --add channels conda-forge

#Nakon toga, instalirajte 3 dodatna paketa:
#IPYLEAFLET:
conda install -c conda-forge ipyleaflet
jupyter nbextension enable --py --sys-prefix ipyleaflet

#LIBROSA:
conda install -c conda-forge librosa

#PYGAME:
pip install pygame


Preostali korišteni paketi (pandas, numpy, matplotlib.pyplot, Ipython.display, itertools, ipywigdets) trebali bi biti instalirani. Ukoliko nisu, možete ih instalirati koristeći conda install <package name>
