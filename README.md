# AndroidSourceFlavoring-I
This repo will demonstrate the android java source flavoring using 1st pattern. This pattern is discouraged to use but still as a learning and to understand how other source favoring patterns evoled you should check this. This pattern of source flavoring mandates to keep more than 1 slightly varing copies of code that should be exposed as part of flavor, in respective flaor java folder.  

In this source flavoring pattern we keep more than 1 copy based on our flavoring requirements, with slight variation in the methods exposed or classes added to specific flavor. 
We need to keep more than1 copy because we want to achieve flavoring asn well as if we keep base source flavor copy in main we'll get duplicate files error.

The flavored copy will get merged with main source folder to create final package.
