<h5>Table Creation</h5>

<ol>
  <li>
    /usr/local/mysql/bin/mysql -u root -p
  </li>
  
  <li>
  create database MOVIEBOOKINGS;
  </li>
  
  <li>
  use MOVIEBOOKINGS;
  </li>

  <li>
    CREATE TABLE login(FIRST_NAME VARCHAR(20),LAST_NAME VARCHAR(20),PHONE_NO INT(12),USERID VARCHAR(20) PRIMARY KEY,PASSWORD INT(4),MOVIE VARCHAR(20),TICKETS INT(2), SNACKS VARCHAR(30), TIME VARCHAR(10));
  </li>

  <li>
    INSERT INTO login VALUES(“AMIT”,”TYAGI”,017658358,”MAPS23”,7890,”3 IDIOTS”,3,”popcorn”,”10:00 am”);
  </li>

  <li>
    INSERT INTO login VALUES(“AMISH”,”VERMA”,012345678,”MATT23”,1234,”3 IDIOTS”,4,”popcorn”,”10:00 am”);
  </li>
  
</ol>
