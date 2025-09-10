

*>* *Create CalendarQuarterName column*





 			*CalendarQuarterName:*= IF('Calendar'\[CalendarQuarter]=1,"Qrt1",
						IF('Calendar'\[CalendarQuarter]=2,"Qrt2",IF('Calendar'\[CalendarQuarter]=3,"Qrt3","Qrt4")))



*> Create Age Column*



 			Age:= DATEDIFF(Customers\[BirthDate],TODAY(),YEAR)





*> Create GroupYear Column*





 			GroupYear:=IF(Customers\[Age]<20,"Less 20",IF(Customers\[Age]<=40,"From 20 to 40","Greater 40"))





*> Create GenderName Column*



 			GenderName:=IF(Customers\[Gender]="M","Male","Female")





