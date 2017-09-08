SQL Projects
/********************************************/

/***The following section contains sql puzzles to be examined

/*****CONSTRAINTS******/
/**instructions - add constraints to the table******/

create table tenants (
  id int,
  firstname varchar(255),
  lastname varchar(255),
  date_movein Date, CONSTRAINT check_date_movein CHECK (date_movein <= sysdate))
  apt_name varchar(150),
  occupation varchar(150),
  );

/**1 - assign all columns not null**********************************************/
/**2 - id is the primary key and assign auto_increment to id ******************/
/**3 - column date_movein should be equal to the current date or past date****/
