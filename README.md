
# Streamlit-Kaggle Connection

This project is is part of my participation in  streamlit connection hackathon app , that use st.experimental_connection in order to connect to a kaggle datasets via kaggle api.


![Logo](https://i.postimg.cc/PfVwHZ2Z/kaggle-streamlit-header.png)


## Usage/Examples

```python
{
conn = st.experimental_connection("kaggle_datasets", type=KaggleDatasetConnection)
df = conn.get(dataset_reference=view_ds, ttl=3600)
}

```


## Installation

Install my-project with pip

```bash
  git clone https://github.com/MohamedLouttHB/streamlit_hack_connection.git
  install requirements.txt
  cd ~ streamlit hack 
  streamlit run main.py
```
    
## Demo

https://st-hack-connection.streamlit.app/

## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


