# Graph-Database-Example
A simple microblog tutorial, example found here [Flask](http://flask.pocoo.org/docs/0.10/tutorial/), that connexts to a neo4j Graph Database.

## Usage

Make sure [Neo4j](http://neo4j.com/download/other-releases/) is running first!

**If you're on Neo4j >= 2.2, make sure to set environment variables `NEO4J_USERNAME` and `NEO4J_PASSWORD`
to your username and password, respectively
If you are using Neo4j >= 3.0 you may need to update your localhost file:**

```
$ export NEO4J_USERNAME=username
$ export NEO4J_PASSWORD=password
```

Or, set `dbms.security.auth_enabled=false` in `conf/neo4j-server.properties`.

Then:

```
git clone https://github.com/DamiPayne/Graph-Database-Example.git
cd Graph-Database-Example
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
python run.py
```

[http://localhost:5000](http://localhost:5000)
