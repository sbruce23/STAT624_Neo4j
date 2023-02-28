# STAT624 Neo4j Docker Environment
**Contents**: Dockerfiles and docker compose for STAT 624 Neo4j environment

## Quick start guide
1. Download zipped folder containing all files in this repository.
2. Unzip folder and store in local directory of your choosing.
3. In a terminal window, navigate to the local directory containing `docker-compose.yml`.
4. Run the command `docker compose up`.  The Docker images will be downloaded to your system and containers will be created accordingly.
5. Open a web browser window and type `localhost:7687` to open the Neo4j GUI to interact with the database.
6. If it requires you to connect, choose the `'No authentication'` connect option.  
7. In one of the tiles, type `:play movie-graph` and hit Enter to load and run queries on the sample movie database.
