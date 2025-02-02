## Hi there 👋

class Engineer:
    def __init__(self):
        self.name = "Inchara"  # Update this with your name
        self.dob = "06/28/2000"  # Update this with your actual DOB
        self.education = {
            "college": "Indiana University Bloomington",
            "degree": "Masters in Computer Science)"
        }
        self.skills = ["Web Development", "ETL", "SQL", "Cloud", "Debugging Life Choices"]
        self.experience = {
            "2025": "Data Engineer - Web Developer @ Project 990",
            "2024": "Teaching Assisstant: Software Engineering / Database Management",
            "2022": "Software Engineer at Sony India"
        }
        self.hobbies = ["Automating Everything", "Googling Errors", "Debugging at 3 AM"]
    
    def __str__(self):
        return f"{self.name}, a Software Engineer/Data Engineer in the making! 🚀"

    def work_life_balance(self):
        return "print('Work-Life Balance Not Found, Please Try Again Later!')"

    def coffee_intake(self):
        return "return '☕' * 5  # Daily Recommended Dose"

# Instantiate your profile
user_profile = Engineer()
print(user_profile)
print(user_profile.work_life_balance())
print(user_profile.coffee_intake())

