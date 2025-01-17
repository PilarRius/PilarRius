    class PilarRius:
        def __init__(self):
            self.name = "Pilar Rius"
            self.title = "World Citizen | Tech & Data Enthusiast"
            self.current_role = "Tech Solutions & Data Scientist at FAO/UN"
            self.skills = [
            "Python", "R", "Vue", "React", "JavaScript", 
            "TypeScript", "Nuxt", "Express"
        ]
        self.email = "pilarriusm@gmail.com"
    
    def about_me(self):
        return f"""
        👋 Hi, I'm {self.name}, a {self.title}.
        👀 I'm interested in finding solutions to real problems.
        🌱 Currently, I'm working as a {self.current_role}.
        💞️ I'm looking to collaborate on projects with others.
        📫 Reach me at {self.email}.
        """

    def coding_skills(self):
        return f"""
        🛠️ Coding Skills:
        - {', '.join(self.skills[:2])}
        - Learnt on the job: {', '.join(self.skills[2:])}
        """

# Create an instance of PilarRius
pilar = PilarRius()

# Display about me and coding skills
print(pilar.about_me())
print(pilar.coding_skills())


