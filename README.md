
hjb3-mysql-reserved-words
========================

This plugin provides a ReservedNames.properties for use by HyperJAXB3. 
It containing all MySQL reserved Words. 

Usage:

    <project>
        [...]
        <build>
           [...]
	   <plugin>
                <groupId>org.jvnet.hyperjaxb3</groupId>
                <artifactId>maven-hyperjaxb3-plugin</artifactId>
                <version>${hyperjaxb3.version}</version>
                <dependencies>
                    <dependency>
                        <groupId>hjb3-mysql-reserved-words</groupId>
                        <artifactId>hjb3-mysql-reserved-words</artifactId>
                        <version>1.0-SNAPSHOT</version>
                    </dependency>
                </dependencies>
                <executions>
	        [...]
                </executions>
            </plugin>
            [...]
        <build>
        [...]
    <project>
