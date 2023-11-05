## mvn-hello-world

This is a simple package that you can use git to pull down and test "mvn" with.

## Clone

```bash
git clone https://github.com/tlh45342/mvn-hello-world.git
```

## STRUCTURE

    ├── src                            src sub 
    |   └─ main                        main sub  
    |      └─ java                     java sub 
    |         ├─ com                   com sub       
    |         |  └─ tlh45342           tlh45342 sub.  Note that tlh45342.com form the basis where code project is used at
    |         |    └─ HelloWorld.java  The actual code.            
    |         └─ resources             Directory is blank - there are no resources, but structure is maintained.
    ├── README.md                      This file
    └── pom.xml                        "Project Object Model" this defines how mvn performs   

# quick-note: lifcycle command 

mvn command that executes a lifecycle choice, in this case the 'package' selection which would compile and build class.

```bash
mvn package
```
