Customer Manager fullREST api

	this api use persistence to set the mysql database

	tomcat SERVER need to be configured in order to run in IDE Eclipse

frameworks used 

	spring and hibernate

mysql setting:

CREATE SCHEMA `salesdb` ;

CREATE TABLE `salesdb`.`customer` (
  `id` INT NOT NULL AUTO_INCREMENT,
  `name` VARCHAR(45)  NOT NULL,
  `email` VARCHAR(45) NOT NULL,
  `address` VARCHAR(45)  NOT NULL,
  PRIMARY KEY (`id`));