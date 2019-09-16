1.Create java files to make this code compile and run.

2.What five objects are created in the main?
List<Dog> dogs = new ArrayList<Dog>(); 
new Comparator<Animal>()
new Dog("Fido", 4)
new Dog("Fido", 3)
new Dog("Alfie", 4)
3.Can you spot the Comparator constructor call? 
new Comparator<Animal>()

Where is the class definition for the Comparator?
@Override
public int compare(Animal a, Animal b){

			    return a.getLegs() - b.getLegs();
			}