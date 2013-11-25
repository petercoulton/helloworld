helloworld
==========

Hello World in a bunch of languages

### Erlang

	% erl -compile hello
	% erl -noshell -s hello hello_world -s init stop

### Go

    % go run hello.go

### Groovy

    % groovy hello.groovy

### Haskell

    % runghc hello.hs

### Java

    % javac Hello.java && java Hello

### PowerShell

	% powershell -File hello.ps1

If you get an error stating that running scripts is disabled, you'll need to [set your ExecutionPolicy][powershell-execution-policy] to trust scripts you write yourself:

	PS > Set-ExecutionPolicy RemoteSigned

### Python

    % python hello.py

### Scala

    % scala hello.scala



[powershell-execution-policy]: http://technet.microsoft.com/en-us/library/ee176949.aspx#EEAA

