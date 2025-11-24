class Roommate:
    def __init__(self, name, age, hobbies, personality):
        self.name = name
        self.age = age
        self.hobbies = hobbies
        self.personality = personality


def main():
    roommate = Roommate(
        name="Eric Mbugua Jones",
        age=25,   # change if you want
        hobbies="reading, football, gaming",
        personality="calm, friendly, and funny"
    )

    print("--- Roommate Information ---\n")
    print("Name:", roommate.name)
    print("Age:", roommate.age, "years old")
    print("Hobbies:", roommate.hobbies)
    print("Personality:", roommate.personality)

    print("\nMy roommate is", roommate.name + ".", "He is",
          roommate.age, "years old, enjoys", roommate.hobbies + ",",
          "and he is very", roommate.personality + ".")


if __name__ == "__main__":
    main()
