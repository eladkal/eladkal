## Hi there, my name is Elad! 👋

- 🔭  I'm specially interested in data engineering and data pipelines platforms.
- 💬  Follow me on Twitter ([@eladkal](http://twitter.com/eladkal)) to stay updated on my latest adventures.
- :mailbox: You can reach me on [Linkedin](https://www.linkedin.com/in/elad-kalif-811b4887/)
- :runner: My faviorte sport is Trail Running.


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class DataEngineer:

    def __init__(self):
        self.name = 'Elad Kalif'
        self.role = 'Data Engineer'
        self.location = 'Tel Aviv'
        self.linkedin = 'https://www.linkedin.com/in/elad-kalif-811b4887/'
        self.knowledge_base = [
            'Software Engineering',
            'Data Pipelines',
            'Python',
            'SQL',
            'Various DBs',
            'Query Optimizations',
            ]
        self.knowledge_base.insert(0, 'Apache Airflow')

    def say_hi(self):
        print("""Hello, thanks for dropping by!

This is {name}, I live in {location}. I work as a {role} and my main focus is {focus}.

I have wide interests, but most of them are {knowledge_base}.

You can contact me on Linkedin: {linkedin}""".format(
            name=self.name,
            location=self.location,
            role=self.role,
            focus=self.knowledge_base[0],
            knowledge_base=', '.join(self.knowledge_base[1:]),
            linkedin=self.linkedin,
            )
        )


me = DataEngineer()
me.say_hi()


```
