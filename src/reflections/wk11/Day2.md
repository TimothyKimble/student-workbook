# Relationships (Day 2)

## What is the difference between a primary key and a foreign key
A primary key is a column or a set of columns in a table whose values uniquely identify a row in the table. A foreign key is a column or a set of columns in a table whose values correspond to the values of the primary key in another table.
## What is an Alias?
Aliases are for lengthy fully qualified names or class names. This can come in handy if there is a long namespace or class name that you do not want to have to keep typing out each time. The alias lives within the scope of the namespace it Is declared in.
## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:
CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)

@"SELECT
d.*,
p.*
FROM patients p
JOIN doctors d ON d.id = p.patiendId
;";

## Afternoon Challenge 
https://github.com/TimothyKimble/Contractor