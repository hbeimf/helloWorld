add deps 

http://mvnrepository.com/

search groupId/artifactId/version

run demo

	$ sbt run

	print like this
	[info] Loading project definition from /web/helloWorld/project
	[info] Set current project to helloWorld (in build file:/web/helloWorld/)
	[info] Running HelloWorld 
	Hello, world!
	[success] Total time: 0 s, completed 2017-5-16 10:55:19


sbt package

	$ sbt package 
	$ ll ./target/scala-2.12/
	
	print like this
	/helloWorld$ ll ./target/scala-2.12/
	drwxrwxr-x 3 xxx xxx 4096  5月 16 13:58 ./
	drwxrwxr-x 5 xxx xxx 4096  5月 16 13:52 ../
	drwxrwxr-x 2 xxx xxx  5月 16 13:50 classes/
	-rw-rw-r-- 1 xxx xxx 1819  5月 16 13:58 helloworld_2.12-0.0.1.jar





