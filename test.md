copy citybike.bikeinfo12
from 's3://citybike1-kiwony/file-num-12/'
credentials 'aws_access_key_id=MY_ACCESS_KEY;aws_secret_access_key=MY_SECRET_ACCESS_KEY'
format
delimiter ','
null as ''
TIMEFORMAT AS 'MM/DD/YYYY HH24:MI:SS'
REMOVEQUOTES;
TEST
