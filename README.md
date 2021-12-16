
# Install the SquirreL SQL ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_squirrelsql

# Clone the SquirreL SQL ansible role. 
git clone git@github.com:computate-org/computate_squirrelsql.git ~/.ansible/roles/computate.computate_squirrelsql
cd ~/.ansible/roles/computate.computate_squirrelsql
```

# Run the SquirreL SQL ansible playbook to install SquirreL SQL locally (requires sudo privileges with -K). 

```bash
ansible-playbook -K install.yml
```

