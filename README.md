# jt (jar tree)

jt is an acronym of Jar Tree. This script is for quick viewing a content of JAR or WAR file as a tree. 

It can be useful when you are making changes to pom.xml file and you want to quickly see the changes.

# Example

Run the command
```sh
$ mvn clean install
```
then
```sh
$ jt target/myproject.jar 
```
the output will be
```sh
.
├── META-INF
│   ├── MANIFEST.MF
│   └── maven
│       └── com.andrey
│           └── project
│               ├── pom.properties
│               └── pom.xml
└── Some.class
```

# Requirements

1. Java 1.7 or newer;
2. <b>tree</b> command. 

# Installation

Currently you have to install the script manually. 

1. Save it to your local machine;
2. Add a folder with the script to $PATH variable;
3. Run <b>source ~/.bash_profile</b> or open a new terminal tab.

# License

MIT
