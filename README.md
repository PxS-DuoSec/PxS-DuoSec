![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=220&section=header&text=SxB🏴‍☠️&fontSize=60&animation=fadeIn&fontAlignY=38&desc=Pentesting%20Scripting%20SystAdmin&descAlignY=51&descAlign=62)

```python
class SxB:

    def __init__(self):
        self.skills = ["Pentest", "Development", "SysAdmin"]
        self.projects = ["RedTeam", "GNU/Linux Distribution"]
    
    def __repr__(self):
        
        t = f"""       
            skills : {", ".join( skill for skill in self.skills )}
            projects : {", ".join( project for project in self.projects )}
        """
        
        return t
        
ax = SxB()
print(ax)

``` 

<a  href="https://discord.gg/XFPs22U9tS">
