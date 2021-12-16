
# Install the gorilla ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_gorilla

# Clone the gorilla ansible role. 
git clone git@github.com:computate-org/computate_gorilla.git ~/.ansible/roles/computate.computate_gorilla
cd ~/.ansible/roles/computate.computate_gorilla
```

# Run the gorilla ansible playbook to install gorilla locally (requires sudo privileges with -K). 

```bash
ansible-playbook -K install.yml
```

