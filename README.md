# Odoo Lab

Odoo requires Python 3.6 or later to run.

Odoo uses PostgreSQL as database management system (supported version: 10.0 and later).

```
sudo -u postgres createuser -s odoo
```

```
git clone -b 12.0 https://github.com/escodoo/odoo-template
```

```
cd odoo-lab
git submodule update --init --recursive
```

```
python -m venv .venv
source ./.venv/bin/activate
```

```
pip install setuptools wheel
```

```
cd odoo/src
pip install -r requirements.txt
```

```
cd ../external-src/oca
../../../install-requirements.sh
```