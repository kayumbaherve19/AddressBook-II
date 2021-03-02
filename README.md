/* Create table*/
CREATE TABLE info (
  id int NOT NULL AUTO_INCREMENT,
  name varchar(45) NOT NULL,
  address varchar(35) NOT NULL,
  phonenumber int NOT NULL,
  PRIMARY KEY (id)
);

/* Select data from DB*/
SELECT * FROM addressbook;

/* Insert data in info Table*/
INSERT INTO info(name, address, " +
							"phonenumber) VALUES (?,?,?) ";


/* Update data in DB */
UPDATE addressbook SET name = ?, address=? , " +
					"phone=? where id=?";
