| Module | File | Method | Path | anonymous | authenticated| administrator | operator | form administrator | P-admin | P-owner | P-operator | P-requisitioner | P-administrator | P-accessioners | P-lab user | P-signout | Comment |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
|Core | routerUser | POST | /user/session |	Y | 															
|Core | routerUser | GET | /user/session | Y |																				
|Core | routerUser | DELETE | /user/session | Y |																	
|Core | routerUser | PUT | /user/session | N | Y |												
|Core | routerUser | POST | /user/session/upgrade |	N | Y |
|Core | routerUser | GET | /user/user | Y |
|Core | routerUser | POST | /user/user/1 | Y |																	
|Core | routerUser | POST | /user/user/2 | Y |																				
|Core | routerUser | POST | /user/user/3 | Y |
|Core | routerUser | POST | /user/user/gdpr | N | Y |																	
|Core | routerUser | POST | /user/user/consent | N | Y |																			
|Core | routerUser | POST | /user/user/consent/mail | N | Y |																		
|Core | routerUser | PUT | /user/user |							
|Core | routerUser | GET | /user/user/profile |	
|Core | routerUser | PUT | /user/user/profile |
|Core | routerUser | POST | /user/user/delete |
|Core | routerUser | POST | /user/user/export |
|Core | routerUser | POST | /user/user/password/mail |													
|Core | routerUser | GET | /user/user/password/reset |										
|Core | routerUser | PUT | /user/user/password |
|Core | routerUser | PUT | /user/user/password/update |															
|Core | routerUser | POST | /user/user/email/update/request |								
|Core | routerUser | POST | /user/user/email/update/mail |								
|Core | routerUser | POST | /user/user/email/update/cancel |								
|Core | routerUser | GET | /user/user/email/update |									
|Core | routerUser | PUT | /user/user/email/update |										
|Core | routerUser | GET | /admin/user/list |									
|Core | routerUser | POST | /admin/user |										
|Core | routerUser | PUT | /admin/user |											
|Core | routerUser | GET | /admin/user |
|Core | routerUser | DELETE | /admin/user |										
|Core | routerUser | GET | /admin/user/profile |												
|Core | routerUser | PUT | /admin/user/profile |													
|Core | routerUser | PUT | /admin/user/email |															
|Core | routerUser | PUT | /admin/user/password |														
|Core | routerUser | POST | /admin/user/export |																		
|Core | routerUser | POST | /admin/user/search |																	
|Core | routerUser | POST | /admin/user/switch |																	
|Core | routerUser | GET | /admin/user/role/list |													
|Core | routerUser | POST | /admin/user/role |																
|Core | routerUser | PUT | /admin/user/role |																
|Core | routerUser | GET | /admin/user/role |													
|Core | routerUser | DELETE | /admin/user/role |		
|Core | routerUser | GET | /admin/user/role/download |		
|Core | routerUser | POST | /admin/group/cud/search |
