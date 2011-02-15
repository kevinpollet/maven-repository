Maven repository
================

Configuration
-------------

To add this repository to your maven project, add the following lines to your `pom.xml` or `settings.xml` file.

### Depencency repository

	<repositories>
	  <repository>
	    <id>releases</id>
	    <url>http://github.com/kevinpollet/maven-repository/raw/master/releases</url>
	  </repository>
	  <repository>
	    <id>snapshots</id>
	    <url>http://github.com/kevinpollet/maven-repository/raw/master/snapshots</url>
	  </repository>
	</repositories>

### Plugin repository

	<pluginRepositories>
	  <pluginRepository>
	    <id>plugin-releases</id>
	    <url>http://github.com/kevinpollet/maven-repository/raw/master/releases</url>
	  </pluginRepository>
	  <pluginRepository>
	    <id>plugin-snapshots</id>
	    <url>http://github.com/kevinpollet/maven-repository/raw/master/snapshots</url>
	  </pluginRepository>
	</pluginRepositories>