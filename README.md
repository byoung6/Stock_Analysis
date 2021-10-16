### Stock_Analysis

**1.Overview of the project**

The purpose of this project is to analyze whether refactoring code will create any substantial differences in the processing speed of the table results in VBA. The refactored code is compared to a tutorial code in order to show whether making core efficiencies to existing code can improve performance. The tutorial code was previously worked on, omitting tickerIndex, and the embedded Arrays of tickerIndex in the three other arrays used in the code.

**2. Analysis**

Overview of the results can show drastic performance improvements from the refactored code to the tutorial code. Performance increased, reducing processing time by approximately 6x. A side by side comparison notes

    2.a 2017 before refactoring and after
  
![2017 before](https://user-images.githubusercontent.com/76926631/137567169-2bcd919a-12a4-47eb-b846-f82c2f9deacc.PNG)![2017 after](https://user-images.githubusercontent.com/76926631/137567165-920376a2-185f-4ea7-9e65-1e0f6ecb9698.PNG)!

    2.b 2018 before refactoring and after
  
![2018 before](https://user-images.githubusercontent.com/76926631/137567173-e695b3aa-b759-449d-9502-3fdf4751c9ec.PNG)![2018 After](https://user-images.githubusercontent.com/76926631/137567172-441fb526-2e2f-498e-b57e-4fc1f2eae1ab.PNG)!

As we can see refactoring this particular code, although not substantial in realtime, can have scaling effects, assuming parallel performance improvements. A six times reduction in processing time scaled may greatly diminish overall wait time for large projects. 

**3. Summary**

    3.a Advantages to Refactoring
    
As noted above, the advantages to refactoring are the possible time benefits from a more efficent code. Not only does the process of refactoring allow for more efficient code, but the process of going through another person's/existing code allows for organizational and formatting cleanups to the existing code. These in turn can allow for different authors to understand the code better, and make their own improvements to it.
    
    3.b Disadvantages to Refactoring
    
The primary disadvantage to refactoring code is the amount of time that can be spent improving, organizing, or even formatting the source code. There may even need to be a cost benefit analysis as to whether the the benefits of refactoring code can outweigh the disadvantages, as a 1 second analysis improvement may be too low of a benefit for hours of refactoring.    
    
    3.c Advantages and disadvantages to the stock sim
    
The pure advantage of refactoring this particular project is to understand the process, and the core benefits. Further, if the code were to be scaled, we can see that a six times performance improvement alone would typically be worth the time spent refactoring. Unfortunately, the actual time saved amounted to approximately 1 second of real time. In non-academic circles, this, in comparison to the amount of time spent refactoring, would have been an organizational waste.     
    
