# mindsdb-tutorials

Tutorial: Getting Started with MindsDB
1. About MindsDB

MindsDB is an open-source AI analytics engine that lets you ask questions across large-scale data sources using natural language or SQL—and get highly accurate answers. It can be deployed locally, in the cloud, or anywhere in between 
GitHub
+1
.

2. Prerequisites

Docker Desktop (or Docker Engine) installed—Docker is the fastest and recommended way to get started 
GitHub
.

3. Installation via Docker
A. Using Docker Desktop (quickest):

Pull & run MindsDB:

docker run -p 47334:47334 -d mindsdb/mindsdb


This command runs MindsDB as a server listening on port 47334 by default.

B. Using Docker CLI:

Clone the repository (optional):

git clone https://github.com/mindsdb/mindsdb.git
cd mindsdb


Customize with Docker Compose or the provided Dockerfile (optional):
Refer to the docker directory and docker-compose.yml for more complex setups 
GitHub
.

4. Core Concepts

MindsDB is built on three pillars:

Pillar	What it Means
Connect	Connect to hundreds of data sources (e.g. MySQL, PostgreSQL, Snowflake) 
GitHub

Unify	Create unified views, knowledge bases, and automate ETL-like jobs via SQL 
GitHub

Respond	Ask your data questions using Agents or interact using the MCP (Model Context Protocol) 
GitHub
5. Quick Usage Guide

Once the Docker container is running:

Access MindsDB’s UI
Typically available at http://localhost:47334/

Connect a data source
Use the UI or SQL to connect—e.g., MySQL, PostgreSQL, or others.

Set up views or knowledge bases
Combine and shape your data using MindsDB SQL capabilities.

Deploy an agent or model
Use Agents to “chat with your data,” or query using MCP.

6. Further Resources

Installation guide for development: 
GitHub

Contribution guide & Code of Conduct: 
GitHub

Community support: GitHub issues, discussions, and Slack 
GitHub

7. Summary Steps

Install Docker.

Run MindsDB via Docker.

Access MindsDB UI (localhost:47334).

Connect your data source.

Build views or set up models/agents.

Ask your data questions or integrate via API.
