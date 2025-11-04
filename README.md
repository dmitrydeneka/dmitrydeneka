```python
class DmitryDeneka:
    name = "Dmitry"
    surname = "Deneka"
    email = "dmitrydeneka@gmail.com"
    discord = "@dmitrydeneka"
    expertise = ["Python", "Java", "JavaScript", "C/C++", "MQL", "HTML", "CSS"]
    interests = ["Running", "Basketball", "Photography"]
    motto = "Never Stop Learning!"

    def __str__(self):
        return f"Hi! I'm {self.name} {self.surname}, a Full-Stack Developer — {self.motto}"

    def favorite_tech(self):
        return self.expertise[0]

if __name__ == "__main__":
    dmitry = DmitryDeneka()
    print(dmitry)
    print("Favorite tech:", dmitry.favorite_tech())
    # Output:
    # Hi! I'm Dmitry Deneka, a Full-Stack Developer — Never Stop Learning!
    # Favorite tech: Python
```