
# St. Augustine CHS - ICS4U, Mr. Fabroa
Notes and Examples for Mr. Fabroa's ICS4U Class


## Folder Structure

The workspace contains two folders by default, where:

- `bin`: the folder to maintain compiled binary files (i.e .class files)
- `src`: the folder to maintain sources(i.e .java files)
- `lib`: the folder to maintain dependencies (i.e .jar files)

## Getting Started
1. Fork this repository
2. Clone or import your fork to your development environment (i.e repl.it or VS Code)
3. In your local repository, add an upstream remote by entering the following in the terminal. 
```
git remote add upstream https://github.com/SACHSTech/Fabroa-ICS4U-NotesExamples.git
```

### Getting Updates from the parent fork
When changes are made to the parent fork (i.e new notes), you will need to pull the changes to your fork/repository
```
git pull upstream main
```

### Pushing Changes to Your Fork
When pushing changes from your local repository to your fork in github, be sure to push to your `origin` remote:
```
git push origin main
```

## Compiling and running examples
We will follow best practices by compiling to the `bin` directory and running the `.class` that was created.
```
javac -d bin src/package/subpackage/YourCode.java
java -classpath bin package.subpackage.YourCode
```
