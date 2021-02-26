## Hi there, my name is Elad! 👋

- 🔭  I'm specially interested in data engineering and data pipelines platforms.
- :bulb: Open source advocate
- :runner: My favorite sport is Trail Running.

## Contact Me

[![Linkedin Badge](https://img.shields.io/badge/-EladKalif-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/elad-kalif-811b4887)](https://www.linkedin.com/in/elad-kalif-811b4887) [![Twitter Badge](https://img.shields.io/badge/-eladkal-blue?style=flat-square&logo=Twitter&logoColor=white&link=https://twitter.com/eladkal)](https://twitter.com/eladkal) [![Gmail Badge](https://img.shields.io/badge/-eladkal@apache.org-blue?style=flat-square&logo=Gmail&logoColor=white)](mailto:eladkal@apache.org)

## 🔧 Technologies & Tools
![](https://img.shields.io/badge/DB-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/DB-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/DB-MsSQL-informational?style=flat&logo=microsoft-sql-server&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/DB-Presto-informational?style=flat&logo=presto&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/DB-Trino-informational?style=flat&logo=presto&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/DB-Snowflake-informational?style=flat&logo=snowflake&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/DB-BigQuery-informational?style=flat&logo=google-cloud&logoColor=white&color=6aa6f8)

![](https://img.shields.io/badge/Tools-Apache--Airflow-informational?style=flat&logo=apache-airflow&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)

![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-SQL-informational?style=flat&logo=sql&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Editor-PyCharm-informational?style=flat&logo=pycharm&logoColor=white&color=6aa6f8)


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class DataEngineer:

    def __init__(self):
        self.name = 'Elad Kalif'
        self.role = 'Data Engineer'
        self.location = 'Tel Aviv'
        self.knowledge_base = [
            'Software Engineering',
            'Data Pipelines',
            'Python',
            'SQL',
            'Various DBs',
            'Query Optimization',
            ]
        self.knowledge_base.insert(0, 'Apache Airflow')

    def say_hi(self):
        print("""Hello, thanks for dropping by!

This is {name}, I live in {location}. I work as a {role} and my main focus is {focus}.

I have wide interests, to name a few {knowledge_base} & {knowledge_base_last}.""".format(
            name=self.name,
            location=self.location,
            role=self.role,
            focus=self.knowledge_base[0],
            knowledge_base=', '.join(self.knowledge_base[:-1]),
            knowledge_base_last=self.knowledge_base[-1]
            )
        )


me = DataEngineer()
me.say_hi()


```
