# Quantum network model [ARCHIVADO]
Conjunto de scripts utilizados para simular, modelar e analizar una red cuantica, donde los grafos se conectan mediante entrelazamiento cuantico
y conectar dos nodos cualesquiera de la red "gasta" el entrelazamiento de los nodos del camino. El conjunto de scripts presentan son parte de la Tesis de licenciatura de Santiago Basañes (defendida en octubre del 2019). 

La estructura del repositorio es la siguiente: 

tesis-quantum-network-model/  
├── analysis/ # herramientas y scripts de analisis  
│   ├── config.py  
│   ├── degree_distribution_analysis.py  
│   ├── entropy_analysis.py  
│   ├── fit_analysis.py  
│   ├── main.py  
│   ├── plots.py  
│   └── tools.py  
│  
├── simulation/ # modelos de redes y la evolucion en su conexion  
│   ├── builder_networks.py  
│   ├── channel_ocupation.py  
│   ├── config.py  
│   ├── main_simulation.py  
│   └── tools.py  
│  
├── equaation/ modelo matemtico que busca replicar el comportamiento de la simulacion  
│   ├── critical_time.py  
│   ├── quiting_path.py  
│   └── solve_equation.py  
│  
├── mini-extra-scripts/ # scripts de pruebas y ploteos  
│   ├── entropy_phase_transition_in_ER.py  
│   ├── graph_graph.py  
│   ├── make_layout.py  
│   ├── plot_6_examples_models.py  
│   ├── plot_two_graph.py  
│   └── tree_first_step.y  
│  
├── stored # donde se guardan los resultados  
├── .gitignore                     # Para evitar subir archivos pesados o temporales
└── README.md                      # Documentación general del repositorio

