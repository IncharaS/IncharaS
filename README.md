# Hi there!

```python
class Engineer:
    def __init__(self):
        self.name = "Inchara"
        self.education = {
            "college": "Indiana University Bloomington",
            "degree": "Masters in Computer Science"
        }
        self.skills = ["Web Development", "ETL", "SQL", "Cloud", "Debugging Life Choices"]
        self.experience = {
            "2025": "Data Engineer - Web Developer @ Project 990",
            "2024": "Teaching Assistant: Software Engineering / Database Management",
            "2022": "Software Engineer at Sony India"
        }
        self.hobbies = ["Automating Everything", "Googling Errors", "Debugging at 3 AM"]

    def __str__(self):
        return f"{self.name}, a Software Engineer/Data Engineer in the making! 🚀"

    def work_life_balance(self):
        return "print('Work-Life Balance Not Found, Please Try Again Later!')"

    def coffee_intake(self):
        return "☕" * 5  # Daily Recommended Dose

# Instantiate your profile
inchara_profile = Engineer()
print(inchara_profile)
print(inchara_profile.work_life_balance())
print(inchara_profile.coffee_intake())
```
