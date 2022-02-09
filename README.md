# Test repository for DT-DATA

This is a testing repository for DT-DATA, it contains a docker-compose.yml file.
to run this repo clone it with git:

```bash
git clone https://github.com/elinarezv/docker-odoo-dt-data.git
```
then change to folder and run with:

```bash
sudo docker-composer up
```
then points your web browser to localhost:8069 and create a new Odoo database.

On Odoo/Applications install **Odoo module for DT-DATA test**  module.
Grant to user(s) Manager permissions to module on Settings/Users (Loans)

That's all