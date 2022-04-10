# Bank-note-auth
Complete execution of a data science project. Created a bank Note authentication web API using Python, Flask. Used Docker for containerization of the app
<hr/>
For Creating Contaer used Docker-<br />
<br />
-> Required libraries are written in requirment.txt.<br />
-> The App file is flask_api.py<br />
-> Model is exported in pickle format classifier.pkl. The model has an accuracy on 98.6%<br />
-> Docker file container code for creating docker container. It specifies things such as<br /><br />
      From  Base image - continuumio/anaconda3<br /><br />
      COPY Copy data from current directory to "/usr/app/" in container<br /><br />
      Expose 5000 The port number from which container should get all the information from<br /><br />
      WORKDIR The current working dir of the container "/usr/app/"<br /><br />
      RUN pip install -r requirments.txt run this comment while creating the container for installing all the required dependencies<br /><br />
      CMD python flask_api.py default execution of file once the contaner is set to run.<br /><br />
   
