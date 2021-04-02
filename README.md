# CalculatorV1.5
 
The previous bug was fixed by using 

   bool valid = false;
   
   while (!valid)
			{
			valid = true; 
		
	
			cin>>//required input
			cout<<"\n";

			if(cin.fail()) 
			{
			cin.clear(); 
			cin.ignore(); 
			//error message
			valid = false; 
			}
   
   but new bugs were find like taking operation values in with more than one answer like asking a, s, m.d or e but still taking and reading values in like ad for example which would give an error but still will proceed to ask number values, which later will stuck in a small loop of asking numeric values and giving the error of wrong input
