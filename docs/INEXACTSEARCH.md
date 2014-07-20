Usage
=====

### Note :
This module is still under development and this document presently shows only currently available utilities.

#### Bigram Average
```
        InexactSearch is = new InexactSearch();
        double res = is.bigramAverage("toxicity", "city");
```
The function `bigramAverage(String, String)` accepts two string and returns bigram average value between 0 and 1.

#### Compare
```
        InexactSearch is = new InexactSearch();
        double res = is.compare("ಮಾವಿನ ಹಣ್ಣು", "माविन हण्णु ");
```
The function `compare(String, String)` accepts two string and returns compare value between 0 and 1.


#### Get module name and information
```
        String moduleName = obj.getModuleName();
        String moduleInforamtion =  obj.getModuleInformation();
```

#### To run tests
Tests present at `/src/test/java/`

  - Select test to run
  - Right Click -> Run Test -> Run as Android Test

