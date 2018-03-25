# AndroidSourceFlavoring-I
Pattern-I 

This repo will demonstrate the android java source flavoring using Pattern-I. 
This pattern is discouraged to use but to understand how other source favoring patterns evoled you should check this. 
This pattern of source flavoring mandates to keep more than 1 slightly varying copies of code that should be exposed as a part of flavor, in respective flavor java folder[For linking pls refer sdk_facade-> build.gradle file].  

In this source flavoring pattern, we keep more than 1 copy based on our flavoring requirements, with slight variation in the methods exposed or classes added to specific flavor. 
We need to keep more than1 copy because we want to achieve flavoring as well. 
If we keep same source flavor copy in main source folder we'll get duplicate files error by IDE(Because at the time of merge/compile compiler will get confuse with same files in same hierarchy).

The flavored copy will get merged with main source folder to create final package.
