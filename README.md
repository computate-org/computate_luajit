
# Install the luajit ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_luajit

# Clone the luajit ansible role. 
git clone git@github.com:computate-org/computate_luajit.git ~/.ansible/roles/computate.computate_luajit
cd ~/.ansible/roles/computate.computate_luajit
```

# Run the luajit ansible playbook to install luajit locally. 

```bash
ansible-playbook install.yml
```

