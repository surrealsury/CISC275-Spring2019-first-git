# CISC275-Fall2018-first-git
1. Create java files to make this code compile and run.


2. What five objects are created in the main?

	3 Dogs: Fido, Fido and Alfie

	1 ArrayList named dogs
	
	1 Collection


3. Can you spot the comparator constructor call? Where is the class definition for the comparator?

The comparator constructor call: 
Collections.sort(dogs, new Comparator<Animal>(){
			@Override
			public int compare(Animal a, Animal b){
			    return a.getLegs() - b.getLegs();
			}
		});

