# Exhibits Vagrant Environment

1. `git clone https://github.com/mlibrary/exhibits-vagrant`
1. `vagrant up`
1. Get the exhibits sql and files directories from box.
1. Load the sql with something like `gunzip -c < exhibits.sql.gz | vagrant ssh -- mysql -u root exhibits`
1. Load the files directories with something like `(cd sites/exhibits/ && tar xzf exhibits-files.tar.gz)`
1. Add an entry in `/etc/hosts` like `10.255.21.11    exhibits.local`

