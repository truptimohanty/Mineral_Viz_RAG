# Mineral_Viz_RAG

### AI Assistance to Global Mineral Resource Analysis and Visualization
1. Clone/download the repository to your local system.

2. Open a terminal and change the directory to the repository directory
   ```
   cd \path\to\repository\
   ``` 
4. Run the following command to install the necessary dependencies.
   ```
   pip install -r requirements.txt
   ```
5. Execute the following command to start the application.
   ```
   python app.py
   ```
6. Open your web browser and go to
     http://127.0.0.1:8080

### How to use your own data for querying

1. The data preferably in PDFs or CSV formatn required to be placed in the user_data directory.

2. Execute the following command to create a custom VectorDB that enables the LLM to interact with and query this custom database. 
   ```
   python data_to_VectordB.py
   ```
3. Execute the following command to start the application.
   ```
   python app.py
   ```
4. Open your web browser and go to
     http://127.0.0.1:8080
