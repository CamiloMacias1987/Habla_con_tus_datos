# Habla_con_tus_datos

Autor:

Juan Camilo Macías Betancur Data Analyst | Data Scientist

Abstracto:

El archivo LLM_para_excel.py contiene el código para poder interactuar con el archivo de excel que uno desee, se usa la librería streamlit para generar la interfaz que permite dicha interacción. De la librería LangChain se importa create_pandas_dataframe_agent para poder interactuar con datos tabulares y se usa ChatGroq como "agente de IA". El archivo config.toml contiene la API de Groq que conecta al "agente de IA". Es importante mencionar  para que este código pueda funcionar se debe de realizar las siguientes instalaciones:

pip install streamlit
pip install langchain_experimental
pip install langchain_groq
pip install openpyxl
pip install tabulate

También es importante mencionar que para poder conocer la dirección IP donde se aloja la interfaz con la que vamos a interactuar con el archivo de excel se debe de ejecutar el siguiente código:

streamlit run C:\Users\XCY\Desktop\Carpeta_principal\LLM_para_excel.py (Cambiar ruta donde se encuentra el archivo .py en cuestión)

Una vez se entre en la interfaz en el localhost se debe de subir el archivo de excel con el que se desea interactuar con el botón "Browse files" y por medio de la barra de mensajes se ingresan las preguntas que se le quieran hacer al archivo de excel.
