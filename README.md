# piggy
code to count piggs 
class Garden:
    def __init__(self):
        self.pigs = []

    def add_pig(self, pig_name):
        self.pigs.append(pig_name)

    def count_pigs(self):
        return len(self.pigs)

# Create a garden
my_garden = Garden()

# Add pigs to the garden
my_garden.add_pig("Piggy")
my_garden.add_pig("Porky")
my_garden.add_pig("Bacon")

# Count the pigs in the garden
number_of_pigs = my_garden.count_pigs()
print(f"There are {number_of_pigs} pigs in the garden.")
