"""
Personal developer profile.
This file represents my skills, education, and future goals as a developer.
"""

print(r"""
███╗   ██╗██╗██╗  ██╗ ██████╗ ██╗      █████╗ ██╗
████╗  ██║██║██║ ██╔╝██╔═══██╗██║     ██╔══██╗██║
██╔██╗ ██║██║█████╔╝ ██║   ██║██║     ███████║██║
██║╚██╗██║██║██╔═██╗ ██║   ██║██║     ██╔══██║██║
██║ ╚████║██║██║  ██╗╚██████╔╝███████╗██║  ██║██║
╚═╝  ╚═══╝╚═╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚═╝  ╚═╝╚═╝

███████╗██╗   ██╗███████╗██████╗ ████████╗███████╗███████╗
██╔════╝██║   ██║██╔════╝██╔══██╗╚══██╔══╝██╔════╝██╔════╝
█████╗  ██║   ██║█████╗  ██████╔╝   ██║   █████╗  ███████╗
██╔══╝  ██║   ██║██╔══╝  ██╔══██╗   ██║   ██╔══╝  ╚════██║
██║     ╚██████╔╝███████╗██║  ██║   ██║   ███████╗███████║
╚═╝      ╚═════╝ ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚══════╝╚══════╝

████████╗ ██████╗██╗  ██╗ ██████╗ ██████╗  █████╗ ███╗   ██╗ ██████╗ ██╗   ██╗
╚══██╔══╝██╔════╝██║  ██║██╔═══██╗██╔══██╗██╔══██╗████╗  ██║██╔═══██╗██║   ██║
   ██║   ██║     ███████║██║   ██║██████╔╝███████║██╔██╗ ██║██║   ██║██║   ██║
   ██║   ██║     ██╔══██║██║   ██║██╔══██╗██╔══██║██║╚██╗██║██║   ██║██║   ██║
   ██║   ╚██████╗██║  ██║╚██████╔╝██████║ ██║  ██║██║ ╚████║╚██████╔╝╚██████╔╝
   ╚═╝    ╚═════╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝  ╚═════╝     


      """)
class DeveloperProfile:
    def __init__(self):
        self.name = "My name is Nikolai Fuertes Tchobanou"
        self.aboutme1 = "I am 30 years old, i born in Bolivia and actually live in Spain, passionate about programming, Video games, Data bases and technology"
        self.aboutme2 = "I work a loot as Werehouse operative supervisor in Formula 1, but my dream is to become a professional developer"
        self.role = "Cross-Platform Application Developer & future Computer Systems Engineering and Data specialist"
        self.education = "Currently studying Multiplatform Application Development (DAM)"
        self.skills = ["Python", "Java", "SQL", "HTML5", "CSS3", "C++"]
        self.goals = [
            "Finish DAM with strong programming fundamentals",
            "Enroll in Computer Systems Engineering degree",
            "Build solid backend and mobile projects such as Databases and Android Games",
            "Land a junior developer position, where i can grow and contribute",
            "Continue learning clean code and best practices", 
            "Finish a Masters degree in Big Data or AI"
        ]

    def info(self):
        return f"{self.name} | {self.role}"
    
    def aboutme(self):
        return f"{self.aboutme1}\n{self.aboutme2}"

    def summary(self):
        return f"{self.education} | Skills: {', '.join(self.skills)}"

    def future_goals(self):
        return "\n- " + "\n- ".join(self.goals)


if __name__ == "__main__":
    profile = DeveloperProfile()
    print("About me:", profile.info())
    print(profile.aboutme())
    print("What I do:", profile.summary())
    print("Future goals:", profile.future_goals())
