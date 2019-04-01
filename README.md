# java-rmi-example

java-rmi-example is an example of RMI.

## Installation

Extracted from [javatpoint.com/RMI](https://www.javatpoint.com/RMI).

Java RMI Example
The is given the 6 steps to write the RMI program.

1. Create the remote interface
2. Provide the implementation of the remote interface
3. Compile the implementation class and create the stub and skeleton objects using the rmic tool
4. Start the registry service by rmiregistry tool
5. Create and start the remote application
6. Create and start the client application


## For running this rmi example
  
1. compile all the java files
```bash
javac *.java
```
2. create stub and skeleton object by rmic tool 
```bash
rmic AdderRemote  
```
3. start rmi registry in one command prompt
```bash
rmiregistry 5000
```
4. start the server in another command prompt
```bash
java MyServer
```
5. start the client application in another command prompt


## License
[MIT](https://choosealicense.com/licenses/mit/)