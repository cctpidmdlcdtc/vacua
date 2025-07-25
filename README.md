# vacua

**Vacua** is a radically transparent and minimally invasive deployment environment, built on **Ansible**.
Its technical philosophy is rooted in **indifference** — it doesn’t care what’s there; it only cares that the final state is correct.
It simply executes **exactly what you declare**, with no surprises.

## Installation

```shell
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run

```shell
ansible-playbook deploy.yml -i inventory/hosts
```
