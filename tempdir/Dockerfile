FROM python

# Installation de Flask
RUN pip install flask

# Copie des fichiers nécessaires
COPY ./static /home/myapp/static/
COPY ./templates /home/myapp/templates/
COPY sample_app.py /home/myapp/

# Exposition du port
EXPOSE 5050

# Commande d'exécution
CMD python /home/myapp/sample_app.py
