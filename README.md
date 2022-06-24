# SciModeler-dashboard
project 'Solving Societal Health Challenges with Data Science'

This is the readme file for our SciModeler dashboard.

Following will be the steps how you should use the SciModeler dashboard:

1. Before you can start using the dashboard, you need Neo4j. Download the Neo4j desktop if you don't have it yet(https://neo4j.com/download/).

2. In Neo4j, creat a new project with a local DMBS, add the .cypher files from annotated articles as the database. When you create the local DMBS, you need to set a password,
and this password will be used later.

3. Running the DMBS, go to the Neo4j Browser-> Project Files, add the .cypher-files of the studies that you want to see back in the dashboard. Start the DBMS of Neo4j by clicking on the 'start' button. 
Then you should see that Neo4j says you are connected as user neo4j to bolt://localhost:7687.

4. Open the DBMS by clicking on 'open'. Click on all the run buttons of the files in the Neo4j desktop to run the files.

5. In the python code, change the username and password in the auth parameter in the graph.run function to your own username and password of Neo4j.

6. Run the python code file on your jupyterhub in Google Chrome, you need to install the libraries that are used in the python code(!pip install py2neo to install py2neo library for example).

7. In the output you will see the address of the localhost of our dashboard, click it to open a new webpage and welcome to our dashboard!

8. For more information about how the dashboard works, we refer to the user manual of the dashboard.


For any technical problems, please be free to contact us.
