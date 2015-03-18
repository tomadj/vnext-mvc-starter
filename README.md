vNext Mvc Starter
================
Mvc starter as vNext  project.

## vNext Environment Installation

The entire process of installing the new K Runtime Environment (KRE)`, `K Version Manager (KVM)` - required to run vNext projects on from a command line, is described on `Home` project page: [https://github.com/aspnet/Home/](https://github.com/aspnet/Home/)

## Running project

1. Clone this repository
2. Change directory to the folder of the sample you want to run
3. Run ```kpm restore``` to restore the packages required by that sample.
4. You should see a bunch of output as all the dependencies of the app are downloaded from MyGet. 
5. Run the sample using the appropriate `k` command:
    - For the console app run  ```k run```.
    - For the web apps run ```k web``` on Windows or ```k kestrel``` on Mono.
6. You should see the output of the console app or a message that says the site is now started.
7. You can navigate to the web apps in a browser by going to "http://localhost:5001" or "http://localhost:5004" if running on Mono.
