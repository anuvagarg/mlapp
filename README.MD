conda create -n ml python=3.9
conda activate ml
conda install streamlit
conda install matplotlib scikit-learn
ipython kernel install --user --name=ml 
jupyter notebook

streamlit run app.py