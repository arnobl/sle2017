
To run the tool to produce the tutorials for both Kompren and Robot unzip `binariesDemo.zip` and:

```
java -jar java -jar docywood.core-0.0.1-SNAPSHOT.jar
```

The generated tutorials are located in the folder `output`.


The Kompren tutorials are available on the [official web page of the Kompren DSL](https://github.com/arnobl/kompren).

The `binariesDemo.zip` archive contains the metamodel, the grammar and the input model used as input for the illustrative example and for Kompren. The generated tutorials for `Robot` are provided as follows:


### <a name="Defining-a-ProgramUnit"></a>Defining a ProgramUnit

```
begin
 end
```
A ProgramUnit contains the commands for controlling a robot. It is the main class of the language. Type `begin`. 

Type `end`. 


### <a name="Defining-a-Move"></a>Defining a Move

```
begin
 	move ( 25 )
 end

```
It defines a command for moving forward the robot. `distance` must be defined. The robot moves foward for a given distance in centimeter. The expected format is a double value.
Type `move (`. 

Then, give the value, here: `25 `.


Type `)`. 

See also:<br/>
[Defining a ProgramUnit](#Defining-a-ProgramUnit)



### <a name="Defining-a-Turn"></a>Defining a Turn

```
begin
 	turn ( -100 )
 end

```
It defines a command for rotating the robot. `angle` must be defined. The robot rotates following a given rotation angle in degree. The expected format is a double value.
Type `turn (`. 

Then, give the value, here: `-100 `.


Type `)`. 

See also:<br/>
[Defining a ProgramUnit](#Defining-a-ProgramUnit)



