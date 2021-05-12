# muma


/configuration>
			</plugin>	
			<!-- Set JDK Compiler Level -->
			<plugin>
				<groupId>org.apache.maven.plugins</groupId>
				<artifactId>maven-compiler-plugin</artifactId> < this is compiler plugin>
				<version>2.3.2</version>
				<configuration>
					<source>${jdk.version}</source>
					<target>${jdk.version}</target>
				</configuration>
			</plugin>
			<!-- For Tomcat -->
			<plugin>
				<groupId>org.apache.tomcat.maven</groupId>
				<artifactId>tomcat7-maven-plugin</artifactId> < this is tomcat plugin>
				<version>2.2</version>
				<configuration>
					<path>/CounterWebApp</path>
				</configuration>
			</plugin>
		</plugins>
	</build>
