FROM continuumio/anaconda3
LABEL maintainer clwei idreamer@gmail.com
RUN pip install --upgrade pip && pip install msgpack plotly && /opt/conda/bin/conda install jupyter -y --quiet && mkdir /opt/notebooks
CMD ["/opt/conda/bin/jupyter", "notebook", "--notebook-dir=/opt/notebooks/", "--ip='*'", "--port=8888", "--no-browser", "--allow-root"]
