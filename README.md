```python
class Anuragh:

    def __init__(self):
        self.username = 'AnuraghSarkar'
        self.name = 'Anuragh Timalsina'
        self.web = 'https://anuragh.netlify.com'
        self.twitter = '@anuragh_js'
        self.code = {
            'frontend': ['HTML', 'CSS', 'JavaScript', 'ReactJS', 'Boostrap', 'TailWind'],
            'backend': ['Python', 'Flask', 'Django', 'NodeJS', 'Express'],
            'database': ['PostgreSQL', 'MySQL', 'SQLite3', 'Mongo DB'],
            'devops': ['Docker', 'Heroku'],
            'tools': ['GIT', 'GitHub', 'Pandas', 'Visual Studio Code', 'Jupyter notebook', 'Redis'],
            'misc': ['Firebase', 'SCRUM', 'GNU/Linux']
        }
        self.architecture = ['SPA', 'MVC', 'PWA', 'microservices']

    def __str__(self):
        return self.name


if __name__ == '__main__':
    me = Anuragh()


```

