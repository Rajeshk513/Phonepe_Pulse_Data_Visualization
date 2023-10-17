# PhonePe Pulse Data Visualization 2018-2023

 # Python packages:
    import pandas as pd
    import psycopg2
    import streamlit as st
    import plotly.express as px
    from streamlit_option_menu import option_menu
    from PIL import Image
    import os
    import gitpython


# Tools Used:
    Psycopg2
    streamlit
    pandas
    ploty

# Approach:

    Phonepe-pulse Data extraction: Cloning the Github using script to fetch the data from the Phonepe pulse Github repository and storing it in a suitable format such as CSV or JSON.

    Data transformation: Using a scripting language such as Python, along with libraries such as Pandas, to manipulate and pre-process the data. This includes cleaning the data, handling missing values, and transforming the data into a format suitable for analysis and visualization.

    Database insertion: Using the "psycopg2" library in Python to connect to a PostgreSQL database and insert the transformed data using SQL commands.

    Dashboard creation: Using the Streamlit and Plotly libraries in Python to create an interactive and visually appealing dashboard. Plotly's built-in geo map functions are used to display the data on a map and Streamlit is used to create a user-friendly interface with multiple dropdown options for users to select different facts and figures to display.

    Data retrieval: Using the "psycopg2" library to connect to the PostgreSQL database and fetch the data into a Pandas dataframe. Using the data in the dataframe to update the dashboard dynamically.

    This approach leverages the power of Python and its numerous libraries to extract, transform, and analyze data, and to create a user-friendly dashboard for visualizing the insights obtained from the data




