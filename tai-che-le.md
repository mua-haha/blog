 merge into f\_bankdata\_base t

 using F\_BANKDATA\_TEMP b

 on\( t.ID\_CARD\_VALUE = b.ID\_CARD\_VALUE\)

 when matched then

 update set t.BANKCHECK\_STATUS = b.BANKCHECK\_STATUS

  


