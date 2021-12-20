
# Install the SquirreL SQL ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_squirrelsql

# Clone the SquirreL SQL ansible role. 
git clone git@github.com:computate-org/computate_squirrelsql.git ~/.ansible/roles/computate.computate_squirrelsql
cd ~/.ansible/roles/computate.computate_squirrelsql
```

# Run the SquirreL SQL ansible playbook to install SquirreL SQL locally. 

```bash
ansible-playbook install.yml
```

# Setup Drivers and Connections in SquirreL SQL

## Setup a MySQL driver

- Download the "Platform Independent" driver here: https://dev.mysql.com/downloads/connector/j/
- Extract the mysql-connector-java-8.0.27.jar to this directory: ~/.local/opt/squirrel-sql/lib
- In SQuirreL SQL, click the Drivers tab, then double click on "MySQL Driver"
- Click the "Extra Class Path" tab and add this file: ~/.local/opt/squirrel-sql/lib/mysql-connector-java-8.0.27.jar

## Setup a MySQL connection

- In the Aliases tab, click the [ + ] button. 
- Provide a name for your connection and the JDBC URL to your MySQL database and the username and password (jdbc:mysql://127.0.0.1:3306/mydb?useSSL=false). 
- Click [ Test ] button to test the connection, then click [ Connect ] to connect. 


