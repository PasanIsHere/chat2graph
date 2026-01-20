## Setting Up Your `.env` File

## Setting Up Your `.env` File

This project needs a few secret values (like your database password / api keys) to run.
We keep these in a special file called `.env`.

1. In the root of this project, create a new file named:

```
.env
```

> On most systems, this is just a normal text file. Make sure the name is exactly `.env` (including the dot at the start).

2. Open the `.env` file and paste in the following:

```
NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=your_password
```

3. Replace `your_password` with the password for your local Neo4j database.This project needs a few secret values (like your database password) to run.
   We keep these in a special file called `.env`.

1) In the root of this project, create a new file named:

```
.env
```

> On most systems, this is just a normal text file. Make sure the name is exactly `.env` (including the dot at the start).

2. Open the `.env` file and paste in the following:

```bash
NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=your_password
```

3. Replace the values, like`your_password`, with your actual values / keys .

