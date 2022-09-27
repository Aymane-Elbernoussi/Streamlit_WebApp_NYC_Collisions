# Streamlit_WebApp_NYC_Collisions
This application is a Streamlit web app dashboard that can be used to analyze motor vehicle collisions in NYC. Data is from https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95 (2020)


The dashboard is completely interactive and includes 
- A 2D map visualization using the longtittude and latitude included in the raw data
- st.slider() implemented to let you filter collisions visualized by how many people injured
- st.selectbox() implemented to let you filter collisions visualized by who was injured (Cyclists, Motorists, Pedestrian) 
- A 3D map integration using Uber's open source deck.gl frame work 
- A plotly express histogram to visualize collisions from NYC in 2020 by minute in the hour chosen.

Imports include 
- NumPy
- Pandas
- deck.gl
- plotly express

# In Progress 
I will try to host this app with Heroku to have the web app available from the cloud 
## Today's Progress
- Day 1 (09/19/22): Installed Heroku after building this web app locally, looking how I will implement Heroku to have it available for everyone to click in, still reading documentation 
