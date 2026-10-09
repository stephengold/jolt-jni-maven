[The jolt-jni-maven project][project] provides
a sample desktop application
for [the Jolt-JNI physics library][joltjni],
built using Maven and Java.

Complete source code is provided under
[a 3-clause BSD license][license].


## How to build and run jolt-jni-maven from source

To build the project:

1. Install a [Java Development Kit (JDK)][adoptium],
   version 11 or higher,
   if you don't already have one.
2. Point the `JAVA_HOME` environment variable to your JDK installation:
   (In other words, set it to the path of a directory/folder
   containing a "bin" that contains a Java executable.
   That path might look something like
   "C:\Program Files\Eclipse Adoptium\jdk-21.0.12-hotspot"
   or "/usr/lib/jvm/jdk-21.0.12+8" or
   "/Library/Java/JavaVirtualMachines/zulu-21.jdk/Contents/Home" .)
  + using Bash or Zsh: `export JAVA_HOME="` *path to installation* `"`
  + using [Fish]: `set -g JAVA_HOME "` *path to installation* `"`
  + using Windows Command Prompt: `set JAVA_HOME="` *path to installation* `"`
  + using PowerShell: `$env:JAVA_HOME = '` *path to installation* `'`
3. Install [Maven], if you don't already have it.
4. Download and extract the jolt-jni-maven source code from GitHub:
  + using [Git]: `git clone https://github.com/stephengold/jolt-jni-maven.git`
5. `cd jolt-jni-maven`
6. `mvn package`

To run the "HelloJoltJni" application:
  + `mvn exec:java`


[adoptium]: https://adoptium.net/temurin/releases/ "Adoptium Project"
[fish]: https://fishshell.com/ "Fish command-line shell"
[git]: https://git-scm.com "Git version-control system"
[joltjni]: https://stephengold.github.io/jolt-jni-docs "Jolt-JNI project"
[license]: https://github.com/stephengold/jolt-jni-maven/blob/master/LICENSE "jolt-jni-maven license"
[maven]: https://maven.apache.org/ "Maven Project"
[project]: https://github.com/stephengold/jolt-jni-maven "jolt-jni-maven project"
