H2 adatb�zis ne felejtse el az adatokat, az application.properties-be ezt kell �rni:


spring.datasource.url=jdbc:h2:file:c:\\JavaProjects\\testvaadinjpa03;DB_CLOSE_ON_EXIT=FALSE;AUTO_RECONNECT=TRUE
spring.datasource.username=sa
spring.datasource.password=
spring.datasource.driver-class-name=org.h2.Driver
spring.jpa.hibernate.ddl-auto=update