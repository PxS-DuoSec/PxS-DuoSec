```python
class PxS:

    def __init__(self):
        self.skills = ["Pentest", "Development", "SysAdmin"]
        self.projects = ["RedTeam", "GNU/Linux Distribution"]
    
    def __repr__(self):
        
        t = f"""       
            skills : {", ".join( skill for skill in self.skills )}
            projects : {", ".join( project for project in self.projects )}
        """
        
        return t
        
ax = PxS()
print(ax)

``` 
---

<h2>Join Us !</h2>

<img width="31" src="https://logo-marque.com/wp-content/uploads/2020/12/Discord-Logo.png"><a href="https://discord.gg/XFPs22U9tS">PxS SecServer</a><br>

<img width="31" src="https://www.specialolympics.asso.fr/wp-content/uploads/2020/04/youtube-logo-icon-transparent-32.png"><a href="https://www.youtube.com/channel/UCCO-FLxIHmk9UqsdUWLF-zg">PxS Computricks</a>

