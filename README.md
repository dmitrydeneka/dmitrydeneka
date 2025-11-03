```python
class DmitryDeneka:
    # Identification & Philosophy
    NAME = "Dmitry"
    SURNAME = "Deneka"
    MOTTO = "Never Stop Learning."

    # Contacts
    EMAIL = "dmitrydeneka@gmail.com"
    DISCORD = "dmitrydeneka"

    # Skills and interests
    EXPERTISE = ["Python", "Java", "C/C++", "JavaScript", "MQL", "HTML", "CSS"]
    INTERESTS = ["Running", "Basketball", "Photography"]

    def __str__(self):
        return f"Hi! I'm {self.NAME} {self.SURNAME} — Full-Stack Developer."

# Creating an object and outputting it
if __name__ == "__main__":
    dmitry = DmitryDeneka()
    print(dmitry) 
    # Output: Hi! I'm Dmitry Deneka — Full-Stack Developer.
```