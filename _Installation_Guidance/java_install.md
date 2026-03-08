Install Java (OpenJDK)
    sudo apt update
    sudo apt install openjdk-21-jdk -y

Check Java Version
    java -version
    javac -version

Compile and Run a Java Program
    Create file:
        nano Hello.java

Sample code:
    class Hello {
        public static void main(String[] args) {
            System.out.println("Hello from Java!");
        }
    }

Compile:
    javac Hello.java

Run:
    java Hello
