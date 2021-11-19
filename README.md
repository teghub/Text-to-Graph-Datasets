# Text-to-Graph-Datasets

The news can be imported into Neo4j database using "neo4j admin import" command as follows:

FOR WINDOWS

neo4j-admin.bat import --id-type=INTEGER --nodes=NODE_PATH\news.csv --nodes=NODE_PATH\words.csv --relationships=RELATION_PATH\wwr.csv --relationships=RELATION_PATH\nwr.csv --multiline-fields=true --database=graph.db

FOR LINUX

./neo4j-admin import --id-type=INTEGER --nodes=NODE_PATH/news.csv --nodes=NODE_PATH/words.csv --relationships=RELATION_PATH/wwr.csv --relationships=RELATION_PATH/nwr.csv --multiline-fields=true --database=graph.db
