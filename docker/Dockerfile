FROM piacc-latest-notebook

RUN python3 -m pip install --upgrade pip 
RUN pip install notebook; PySpice==1.5,matplotlib>=3.2, klayout==0.30.2, gdstk==0.9.60

WORKDIR /PIACC

RUN git clone https://git.code.sf.net/p/ngspice/ngspice 

# Default command
#CMD ["jupyter", "notebook", "--ip=0.0.0.0", "--port=8888", "--allow-root", "--NotebookApp.token=''", "--NotebookApp.password=''"]
