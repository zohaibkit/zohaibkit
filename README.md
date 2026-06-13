class Zohaib:

    def __init__(self):
        self.name = "Zohaib Khan"
        self.role = "AI Engineer"

        self.skills = {
            "Languages": [
                "Python",
                "JavaScript",
                "C++"
            ],

            "AI": [
                "Machine Learning",
                "Deep Learning",
                "Computer Vision",
                "LLMs"
            ],

            "Tools": [
                "Git",
                "Linux",
                "Docker",
                "VS Code"
            ]
        }

    def mission(self):
        return "Create impactful AI products"

me = Zohaib()
print(me.mission())
