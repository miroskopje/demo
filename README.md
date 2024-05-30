Assumtions:

1. i used LocalDateTime as KEY in order to simplify things with this DEMO. There are potential things that need to be clarified regarding the dates such as what time zone is our server do we need to take into considerations timezones and client time zone ect.
2. The response we have from CoinDesk is used to be returned. In Case we want to extend ans save response in DB we must create our entity and DTO and use modelMapper to convert response to entity and then save the entity and then when we return the result it should be converted to DTO.
3. Tests can and should be added in next phase
4. code comments are not added since this is not production code but its just a demo 
5. performance should be also measured and checked like memory consumption
6. paging can/should be added to optimise response becuase historical records can be potentialy big
7. the format of the dtes for FILTER method is yyyy-MM-dd HH:mm:ss example: 2024-05-29T16:57:39