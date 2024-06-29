```python
class Explorer:
    def __init__(self, name, role, languages_spoken, learning, fun_fact):
        self.name = name
        self.role = role
        self.languages_spoken = languages_spoken
        self.learning = learning
        self.fun_fact = fun_fact

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

def main():
    me = Explorer(
        name="Sasta Hari Haran R",
        role="SDE and FullStack Developer",
        languages_spoken=["hn_In", "en_US"],
        learning="Data Structres and Algorithms",
        fun_fact="An AI a day keeps the developer away"
    )

    me.say_hi()

if __name__ == "__main__":
    main()
```


