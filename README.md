<h2>Hi, I'm Esmé Taylor R.
  <a href="https://github.com/achenalia">
  <img align="right" alt="Esmé's Github" width="23px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
  </a>
  <a href="mailto:esme.taylor.richardson@gmail.com">
  <img align="right" alt="Esmé's Email" width="23px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.1.0/icons/gmail.svg" />
  </a>
</h2>
  
<img align="right" alt="GIF" width="300px" src="https://miro.medium.com/v2/resize:fit:700/1*krJsZsRUsIz3kCEW8VaC0A.gif" /><img align="right" alt="GIF" width="200px" src="https://i.gifer.com/origin/29/290b383afb7c810c0635b6662ea8660d_w200.gif" />



I'm an **EMT** turned **Software Developer** focused on building innovative healthcare solutions to make both patients' and providers' lives easier.

I'm always open to opportunities to collaborate, answer questions, or learn more!

<br />

```python
class ReadMe:
    def __init__(self, username, year):
        self.username = username
        self.pronouns = ["She", "Her"]
        self.ask_me_about = ["software dev", "web dev", "tech"]
        self.technologies = {
            "back_end": ["nodejs", "express", "django", "python"],
            "front_end": ["react"],
            "database": ["postgresql"],
            "dev_ops": ["AWS", "Docker", "Git"],
            "misc": ["Socket.IO"]
        }
        self.year = year
        self.employment = {
            'EMT': ['Emergency Medical Technician', 'Atlanta, Ga'],
            'Developer' : ['Developer', 'Online']            
        }
        self.education = {
            'college': ['Bachelor of Arts in Computer Science (B.A.)', 'University'],
            'programming': ['Self-Taught', 'Projects']
        }

    def doing(self, now):
        today = self.year

        if now < today:
            job = self.employment['EMT']
            school = self.education['college']
            return f"""
            I was working as an {job[0]} in {job[1]} while pursuing a {school[0]} at {school[1]}.
            """
        elif now == today:
            current = self.education['programming']
            return f"""
            I am mostly {current[0]}, learning from my many {current[1]}!
            """
        elif now > today:
            goal = self.employment['developer']
            return f"""
            I am eager to collaborate with other {goal[0]}s, feel free to contact me {goal[1]}.
            """
        else:
            return "To be continued..."

    def collaborate(self, role, organization, location):
        opportunity = self.employment
        opportunity[role] = [organization, location]
        
me = ReadMe('achenalia', 2024)
```
